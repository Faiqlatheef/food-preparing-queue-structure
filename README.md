# food-preparing-queue-structure
Implement queue structure to match below given scenario. And implement add_order, prepare_next_order, and check_status functionalities.

EatItNow restaurant is trying to automate their food preparing pipeline. Once waiter received order from the customer, waiter will add that to the system using add_order function. 
add_order function will take table_number (integer), meal_number (integer) and waiter_id (integer) as parameters in order to add details into the system.
And orders will be saved in first come first serve order.

There is only one chef in the kitchen, he is only capable of processing one order at a given time. chef will use prepare_next_order function to get the next order that available in the system. Calling prepare_next_order function will return table_id, waiter_id and meal_id to the chef.

There is another function called check_status to check what is the status of the order, after providing table_number this function will provide status of the order. If it is already taken by the chef using prepare_next_order function then status will be preparing. Or otherwise it is still in the queue structure. It will provide what is the location of the order in queue. 
