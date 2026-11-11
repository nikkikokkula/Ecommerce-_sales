# E-Commerce Sales Analysis using SQL and Power BI

## Project Overview

This project focuses on analyzing e-commerce sales data using SQL and Power BI. The main objective is to understand sales performance, identify top-performing products, analyze category-wise sales, and track business performance through an interactive dashboard.

The project uses SQL queries to retrieve and analyze data from multiple tables and Power BI to present the results through visualizations and key performance indicators (KPIs).

## Tools and Technologies

- **SQLite** – Database management and SQL queries
- **Power BI Desktop** – Data visualization and dashboard creation
- **SQL** – Data retrieval, filtering, grouping, sorting, and joins
- **DAX** – Creating measures and calculating key business metrics

## Dataset Description

The project uses a sample e-commerce dataset containing four CSV files:

1. **Customers** – Customer details, city, and state.
2. **Products** – Product names, categories, and selling prices.
3. **Orders** – Order details, dates, and order status.
4. **Order Items** – Product quantities and selling prices for each order.

The dataset is created for practice and analysis purposes.

## SQL Analysis

SQL queries were written to perform the following tasks:

- Retrieve and filter customer records.
- Sort customer information.
- Count customers by state.
- Calculate total sales revenue.
- Analyze monthly sales.
- Identify the top 5 products by revenue.
- Calculate the total number of completed orders.
- Calculate total units sold.
- Analyze category-wise revenue.

## Power BI Dashboard

An interactive dashboard was developed in Power BI to present the sales analysis
Key Performance Indicators (KPIs)

Total Revenue

Total Orders

Total Units Sold

Total Customers

Dashboard Visualizations

Monthly Revenue Trend

Category-wise Revenue

Top 5 Products by Revenue

State-wise Revenue

Interactive Filters

Date

Product Category

State

These filters allow users to explore the sales data based on different selections.

Key Findings

Based on the completed-order data:

Total Revenue: ₹1,19,925

Total Units Sold: 91

Total Customers: 18

The dashboard also provides a view of monthly sales trends, product performance, and category-wise and state-wise revenue.

Project Folder Structure

Ecommerce_SQL_PowerBI_Project/
│
├── Dataset/
│   ├── customers.csv
│   ├── products.csv
│   ├── orders.csv
│   └── order_items.csv
│
├── SQL/
│   ├── 01_customer_filter.sql
│   ├── 02_sort_customers.sql
│   ├── 03_customers_by_state.sql
│   ├── 04_total_revenue.sql
│   ├── 05_monthly_sales.sql
│   ├── 06_top_5_products.sql
│   ├── 07_total_orders.sql
│   ├── 08_total_units_sold.sql
│   └── 09_category_sales.sql
│
├── PowerBI/
│   └── Ecommerce_Sales_Dashboard.pbix
│
└── README.md

Learning Outcomes

Through this project, I gained practical experience in:

Writing SQL queries to analyze relational data.

Using JOIN operations across multiple tables.

Applying GROUP BY, ORDER BY, WHERE, and aggregate functions.

Creating DAX measures in Power BI.

Building interactive dashboards using charts, cards, and slicers.

Presenting sales information through meaningful visualizations.

Conclusion

This project helped me understand how SQL and Power BI can be used together to analyze sales data and present useful business insights. It provided practical experience in database querying, data analysis, and dashboard development.

Project Type: Personal Data Analytics Project
Domain: E-Commerce Sales Analysis
Tools: SQLite, SQL, Power BI, DAX
