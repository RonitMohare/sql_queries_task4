# Sql_queries_task4
 Includes SQL queries using SELECT, JOIN, GROUP BY, subqueries, aggregate functions, views, and indexing to analyze e-commerce data using SQLite

📊 Task 4 - SQL for Data Analysis
Internship Task - Data Analyst
Platform Used: SQLiteOnline

🧠 Objective
To gain hands-on experience in using SQL for data analysis by performing the following tasks:

Writing queries using SELECT, WHERE, ORDER BY, GROUP BY, and HAVING

Applying JOINs, subqueries, and aggregate functions

Creating views and indexes for performance

Working with an e-commerce dataset

🛠 Tools & Technologies
Database Engine: SQLite (Memory Mode via SQLiteOnline)

Environment: SQLiteOnline AiDE (Web-based SQL IDE)

Dataset: Self-created eCommerce data with 4 tables:

customers

orders

products

order_details

View: order_summary

✅ Work Done

🔹 Data Insertion

I inserted dummy data into each table for customers, orders, products, and order details to simulate an e-commerce business scenario.

🔹 SQL Operations Performed
1. Basic Queries
Used SELECT, WHERE, ORDER BY to filter and sort customer data

✅ Example: Get all customers from India ordered by name.

3. Aggregations with GROUP BY
Counted customers per country

Calculated SUM and AVG of order amounts per customer

3. Joins
INNER JOIN and LEFT JOIN between customers and orders to fetch order information with names

Noted that RIGHT JOIN is not supported in SQLite (handled accordingly)

4. Subqueries
Found customers who placed orders above the average amount using a subquery

5. Views
Created a view order_summary to summarize order info like customer name, date, and amount

Selected from the view to display aggregated data

6. Indexes
Created indexes on customer_id and order_date to optimize performance
