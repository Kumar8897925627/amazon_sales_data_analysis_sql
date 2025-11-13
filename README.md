# amazon_sales_data_analysis_sql
This project focuses on analyzing Amazon sales data using SQL to uncover key business insights and performance metrics. The goal is to help identify sales trends, profitable product categories, customer purchasing behavior, and regional performance using structured queries and analytical functions.
👇

🛒 Amazon Sales Data Analysis using SQL
📘 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an Amazon Sales dataset downloaded from Kaggle using SQL.
The main objective is to analyze sales performance, customer behavior, and regional trends to extract valuable business insights.
All the analyses are done purely using SQL queries — without the use of Python or other programming languages — demonstrating how SQL alone can be a powerful tool for data exploration and business analytics.

🎯 Objectives

To clean, explore, and analyze Amazon sales data using SQL.

To identify key performance indicators such as total revenue, profit margin, and top-performing products.

To understand customer purchasing patterns and region-wise sales distribution.

To support business decision-making through data-driven insights.

🧩 Dataset Information

Source: Kaggle - Amazon Sales Dataset

Description: The dataset contains detailed records of Amazon sales transactions including product information, customer details, quantities sold, profit, and region-wise performance.

Key Columns:

Order_ID – Unique identifier for each order

Order_Date – Date of the order

Customer_Name – Name of the customer

Region – Region where the order was placed

Product_ID – Unique product identifier

Category – Product category (Electronics, Clothing, etc.)

Quantity – Units sold

Sales – Total sales value

Profit – Profit generated from the sale

🧠 SQL Analysis Performed

The following SQL operations and analytical techniques were applied:

Data Cleaning:

Removed duplicate records and handled null values.

Verified data consistency and corrected data types (e.g., date, numeric).

Exploratory Data Analysis (EDA):

Total and average sales, profit, and quantity sold.

Monthly and yearly sales trends using GROUP BY and date functions.

Top 10 selling products by revenue and quantity.

Category-wise and region-wise performance analysis.

Customer segmentation based on purchase frequency and revenue contribution.

Profit margin calculation for each product and category.

Identification of least-performing products and regions.

Advanced SQL Features Used:

Joins (INNER, LEFT, RIGHT) for multi-table analysis.

Aggregate functions (SUM(), AVG(), COUNT(), MAX(), MIN()).

Window functions for ranking and cumulative calculations.

Subqueries and Common Table Expressions (CTEs).

Views and stored procedures for reusable insights.

📊 Key Insights

The Electronics and Home Appliances categories generated the highest sales revenue.

The Western region consistently outperformed others in both sales and profit.

Certain customers accounted for a large share of repeat purchases — showing strong customer loyalty.

Seasonal patterns were observed with higher sales during festive months.

⚙️ Tools & Technologies

Database: MySQL / Oracle / PostgreSQL

Language: SQL (DDL, DML, DQL)

Optional Visualization: Power BI / Excel for dashboard creation

📈 Outcome

The project successfully demonstrates how SQL can be used for data-driven decision-making in e-commerce analytics.
The insights derived can help Amazon (or similar businesses) in:

Optimizing product inventory.

Improving regional marketing strategies.

Enhancing customer retention through targeted offers.
