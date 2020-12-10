**#ORDER A BURGER MEAL#** 

**POST/meal/lunch/main/burger/burger properties** 

The customer can order one or more beefburger or a veggie burger. The size can be 300 gr or 400 gr. The customer has the option to specify how the burger is cooked: medium rare, medium or well-done. The customer has the option to choose the bun type: white or whole meat. The customer can choose the type of topping for the burger: lettuce, tomato, onion or no topping. The customer can choose which condiment to have with the burger: ketchup, BBQ sauce, mushroom sauce or no condiment.

*__Table showing API burger properties (order burger meal)__* 

| PROPERTY        | DATA TYPE | DESCRIPTION                                                                         | DEFAULT   | MANDATORY/OPTIONAL |
|-----------------|-----------|-------------------------------------------------------------------------------------|-----------|--------------------|
| patty_type      | string    | Specifies the type of burger. Can be "beef" or "veggie".                            | "beef"    | optional           |
| patty_weight    | int       | Specifies the weight of the burger. Can be 300 gr or 400 gr.                        | 300       | optional           |
| patty_cook      | string    | Specifies how the burger is cooked.  Can be "medium rare", "medium" or 'well done". | "medium"  | optional           |
| burger_quantity | int       | Specifies the number of patties to prepare. Acceptable values are 1-3.              | 1         | optional           |
| bun_type        | string    | Specifies the type of bun. Can be  "white" or "whole wheat".                        | "white"   | optional           |
| topping_type    | string    | Specifies the type of toppings. Can be "lettuce", "tomato",  "onion", or  "none".   | "lettuce" | optional           |
| condiment_type  | string    | Specifies the type of condiment. Can be "ketchup", "BBQ sauce" or "none"            | "ketchup" | optional           |



#**


**#ORDER A DRINK#** 

**POST/meal/lunch/drink/drink properties** 

The customer orders a drink and has the option of regular coke or diet coke. The drink order size can be small or large. The customer can order with or without ice.

*__Table showing API drink properties (order drinks)__* 

| PROPERTY   | DATA TYPE | DESCRIPTION                                                          | DEFAULT        | MANDATORY/OPTIONAL |
|------------|-----------|----------------------------------------------------------------------|----------------|--------------------|
| drink_type | string    | Specifies the type of drink.  Can be "regular coke" or  "diet coke". | "regular coke" | optional           |
| drink_size | string    | Specifies the size of drink. Can be "small" or "large".              | "small"        | optional           |
| ice        | string    | Specifies is drink with "ice"  or "no ice".                          | "ice"          | optional           |
