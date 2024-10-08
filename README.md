# Pizza-Sales-Analytics

![](https://github.com/gavi25/Pizza-Sales-Analytics/blob/main/pizza%20sales.png?raw=true)

<h3>Project Overview</h3>

This project involves analyzing pizza sales data to derive meaningful insights and answer key business questions. The analysis covers various aspects of pizza orders, including total revenue, order distribution, and pizza preferences. The goal is to provide actionable insights that can help in strategic decision-making, such as optimizing the menu and improving marketing strategies.

<h3>  Problem Statement </h3>

In the competitive pizza industry, understanding customer preferences and sales patterns is crucial for business success. By analyzing pizza sales data, my aim was to answer several key questions that will provide insights into customer behavior and revenue generation. The analysis will help identify top-performing products, understand sales trends, and optimize inventory and marketing efforts.

<h3> Objectives </h3>

- <h5> Basic Analysis </h5>

    - Retrieve the total number of orders placed.
    - Calculate the total revenue generated from pizza sales.
    - Identify the highest-priced pizza.
    - Identify the most common pizza size ordered.
    - List the top 5 most ordered pizza types along with their quantities.


- <h5>Intermediate Analysis</h5>

    - Join the necessary tables to find the total quantity of each pizza category ordered.
    - Determine the distribution of orders by hour of the day.
    - Join relevant tables to find the category-wise distribution of pizzas.
    - Group the orders by date and calculate the average number of pizzas ordered per day.
    - Determine the top 3 most ordered pizza types based on revenue.


- <h5> Advanced Analysis </h5>

    - Calculate the percentage contribution of each pizza type to total revenue.
    - Analyze the cumulative revenue generated over time.
    - Determine the top 3 most ordered pizza types based on revenue for each pizza category.

<h3> Data Sources </h3>

The following tables are used for the analysis:

- <h4> order_details </h4>

    - order_details_id: Unique identifier for each order detail record.
    - order_id: Unique identifier for each order.
    - pizza_id: Unique identifier for each pizza.
    - quantity: Quantity of the pizza ordered.


- <h4> orders </h4>

    - date: Date when the order was placed.
    - order_id: Unique identifier for each order.
    - time: Time when the order was placed.


- <h4> pizzas </h4>

    - pizza_id: Unique identifier for each pizza.
    - pizza_type_id: Unique identifier for the type of pizza.
    - price: Price of the pizza.
    - size: Size of the pizza.

- <h4> pizza_type </h4>

    - pizza_type_id: Unique identifier for the pizza type.
    - category: Category of the pizza.
    - ingredients: List of ingredients for the pizza.
    - name: Name of the pizza.



<h3>Methodology</h3>

- Data Retrieval

    - Extract data from the above tables using SQL queries.
    - Ensure data integrity and consistency.

- Data Analysis

    - Perform aggregations and calculations to answer the questions.
    - Use data visualization techniques to present insights clearly.

- Advanced Analysis

    - Calculate percentages and cumulative values to understand revenue contributions.
    - Segment data by pizza categories to provide detailed insights.

- Reporting

    - Compile findings into a comprehensive report with visualizations.
    - Provide recommendations based on the analysis.

---

<h3> Contributions </h3>

Contributions are welcome! Please fork the repository and submit a pull request with your changes. 
