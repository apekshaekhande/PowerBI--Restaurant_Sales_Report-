# PowerBI--Restaurant_Sales_Report-
![Screenshot (129)](https://user-images.githubusercontent.com/113659344/210981971-a222505d-9968-442d-82c8-8f69c90a48ad.png)

In this Powerbi Project We have analyze the data and put together a report to help us find opportunities to drive more sales and work more efficiently.
Things are going OK here at Plato's, but there's room for improvement.We've been collecting transacl data for the past year, but really haven't been able to put it to good use. 


Here are some questions that we solved in this project:

Q1 What days and times do we tend to be busiest?

Q2 How many pizzas are we making during peak periods?

Q3 What are our best and worst-selling pizzas?

Q4 What's our average order value?

Q5 what is the month over month sales change of pizza?

Q6 Monthwise analysis of profit.


***Given dataset has following attributes-***

##### 1)order_id: Unique identifier for each order placed by a table

##### 2)order_details_id:Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and            the quantity increases)

##### 3)pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

##### 4)quantity: Quantity ordered for each pizza of the same type and size

##### 5)order_date: Date the order was placed (entered into the system prior to cooking & serving)

##### 6)order_time: Time the order was placed (entered into the system prior to cooking & serving)

##### 7)unit_price: Price of the pizza in USD

##### 8)total_price: unit_price * quantity

##### 9)pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)

##### 10)pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price

##### 11)pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they          all include Tomato Sauce, unless another sauce is specified)

##### 12)pizza_name: Name of the pizza as shown in the menu.

####  Lets see the visuals one by one
## 1)BAR CHART-

![image](https://user-images.githubusercontent.com/113659344/211625632-0accb9f6-e003-4109-8571-7e964d75e50d.png)

####  Here I calcuate Total Orderd quantity per day - On the basis of this chart we conclude that which day in a week has more orders and we can arrange staff on the basis of that 

### 2) DONUT CHART-
![image](https://user-images.githubusercontent.com/113659344/211625467-8d0fd215-6193-4ad4-9fea-c1710ed9aaba.png)
#### Here I use DONUT CHART for showing Total sales of restaurant by category of pizza . It shows higher and lower sales by colour and lables.

### 3) LINE CHART-

![image](https://user-images.githubusercontent.com/113659344/211628203-b3e63380-483c-45dc-ad2b-e6d9dfb3a047.png)

#### In above line chart I show Quantity orderd by month ,year and day basis. here I add hierarchy of date function we can change it into year ,month and day basis. We can also use it by Quarterwise inshort we can see multiple outputs in single visual.

### 3) BAR CHART-
![image](https://user-images.githubusercontent.com/113659344/212560001-9bf30e2e-159f-4418-9e2e-c1dc437ef907.png)

![image](https://user-images.githubusercontent.com/113659344/212560040-203d182a-1b76-4a7c-bcdc-a9cc2b043cff.png)





