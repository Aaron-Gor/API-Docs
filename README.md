# API-Docs

[Get-drink file](Get-drink.md)
@lsnovich

![Workflow Diagram](AaronAPIWorkflow.png)

**##Introduction##**

The overall concept for this embryo API is to take restaurant orders from seated customers, send the orders to the kitchen for preparation and generate a bill at the end of the sitting. The system will be used by: table staff and kitchen staff. The Proof of Concept (POC)at this stage is for a restaurant API for taking food orders, sending the orders to the kitchen, and generating bills. The API takes orders from the restaurant-side by the waiter/waitress and sends the order to the server-side ordering terminal in the kitchen. The orders are printed out for the cooks.

The next stage of the API development will be to develop a tablet-based ordering system for take-away orders. Customers will use a tablet to place orders. The orders will generate a bill which the customer pays. The order is then sent to the kitchen for preparation.


**###POST/meal/lunch/drink/drink properties###**
The customer orders a drink and has the option of regular coke or diet coke. The drink order size can be small or large. The customer can order with or without ice.

| PROPERTY   | DATA TYPE | DESCRIPTION                                                          | DEFAULT        | MANDATORY/OPTIONAL |
|------------|-----------|----------------------------------------------------------------------|----------------|--------------------|
| drink_type | string    | Specifies the type of drink.  Can be "regular coke" or  "diet coke". | "regular coke" | optional           |
| drink_size | string    | Specifies the size of drink. Can be "small" or "large".              | "small"        | optional           |
| ice        | string    | Specifies is drink with "ice"  or "no ice".                          | "ice"          | optional           |
