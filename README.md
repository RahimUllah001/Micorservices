# Micorservices

1: Build an application with fastapi which contain two microserivces
2: Inventory
3: payment

Explanation: These 2 Microservices are communicate with each other through internall API call inventory microservice maintian our stack, when someone order any of the product and also specified the quantity means how many product they want to order. Payment microservice first internall call to the inventory microservice and see amount of the product , if amount of the product is equll or greater then costumer order then condition is statisfied and we pop of message Your order has been successfully submitted if costumer order is greater then remaing the product in our stack then we pop of message Sorry we have insufficient stack
