Project Overview
This project analyzes the sales data of a pizza company to derive valuable insights into sales trends, customer preferences, and revenue generation. 
It uses SQL for querying the data and answers critical business questions to aid decision-making.

Dataset Description
The dataset contains comprehensive details about the pizza sales, including:

Pizza Details: Pizza types, names, sizes, prices, and ingredients.
Order Information: Order dates, times, quantities.


Key Objectives

Total number of orders placed.
Total revenue generated.
Identification of the highest-priced pizza.
Analysis of the most common pizza size ordered.
Identification of the top 5 most ordered pizza types along with their quantities.
Category-wise distribution of pizza quantities ordered.
Hourly distribution of orders.
Grouping orders by date to calculate the average number of pizzas ordered per day.
Determining top 3 pizza types based on revenue.
Percentage contribution of each pizza type to total revenue.
Cumulative revenue analysis over time.
Top 3 pizzas by revenue within each category.


Metrics and Insights
Sales Metrics
Total Orders:
Extracted the count of all orders placed.

Revenue Generated:
Calculated using SUM(price * quantity).

Most Expensive Pizza:
Found the highest price using MAX(price) with corresponding pizza details.

Top Sizes Ordered:
Used COUNT grouped by pizza size to identify preferences.

Profit and Loss Metrics

Top-Selling Pizza Types:
Identified top 5 pizza types based on order quantities.
Calculated their respective contributions to the revenue.

Category-Wise Distribution:
Grouped and calculated the total quantity ordered for each pizza category.

Hourly Order Trends:
Created hourly distribution using the EXTRACT(HOUR FROM order_time) function.


Findings
The most commonly ordered pizza size is Medium.
Cheese Pizza was identified as the highest revenue-generating category.
Revenue shows significant peaks during lunch (12 PM–2 PM) and dinner (6 PM–8 PM).
Vegetarian pizzas dominate in total order quantities.
The Pepperoni Deluxe pizza contributes the highest revenue among all pizza types.


Conclusions
Customer preference leans heavily towards medium-sized pizzas and vegetarian options.
Revenue trends align with standard meal timings, indicating scope for promotional offers during these periods.
Certain premium pizzas, despite lower order counts, significantly impact revenue.
