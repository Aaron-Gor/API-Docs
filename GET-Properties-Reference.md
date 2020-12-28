# GET PROPERTIES REFERENCES 

This section shows the properties, data type, and descriptions required for generating a customer bill (table number, order number, time stamp).

## GET/table number  

*__Table showing properties, data type, and description for GET actions__*

| PROPERTY     | DATA TYPE | DESCRIPTION                                |
|--------------|-----------|--------------------------------------------|
| table_number | int       | The number of the table in the restaurant. |
| order_number | int       | The specific UI assigned to each order.    |
| time_stamp   | date      | The time the order was taken in Unix time. |


## GET HTTP STATUS CODES

Possible server status codes following GET action (Get HTTP Status Codes) can be found [here](https://github.com/Aaron-Gor/API-Docs/blob/main/README.md)


## JSON response schema

curl -X GET "http://URL/tableNo?id=99
tableNo

```
{    “table number”: “5" 

   “orderNum":”123”, 
   "timestamp":"2020-01-21T07:44:45-05:00", 
   "Item1":{      
   "ItemOrdered":{          
   "type":"burgerMeal",          
   "Cost":10.99       
   }    
   },    
   "Item2":{       
   "ItemOrdered":{          
   "type":"salad",          
   "Cost":9.50       
   }    
   }

} ```

