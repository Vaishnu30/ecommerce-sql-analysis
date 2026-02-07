E-Commerce SQL Analysis
📌 Project Overview

This project focuses on analyzing an e-commerce dataset to extract business insights related to customers, orders, revenue, and delivery performance using SQL.

The analysis was performed using a SQLite database, with an emphasis on writing clean, optimized, and business-driven SQL queries.

🎯 Objectives

Analyze customer distribution and behavior

Understand order trends and revenue performance

Evaluate delivery efficiency and logistics costs

Perform data quality checks to ensure reliable analysis

🛠️ Tools & Technologies

SQL (SQLite)

SQLite Database

Power BI (for dashboard visualization)

🗂️ Database Structure

The SQLite database consists of the following tables:

customers

orders

order_items

products

Relationships:

customers → orders → order_items → products

📊 Key Business Questions Answered

How many customers and orders exist overall?

What are the most popular product categories?

Which states generate the highest revenue?

What is the monthly revenue trend?

Who are the top 10 customers by total spending?

What is the average order value?

How efficient is the delivery process?

How much cost is spent on logistics (freight)?

🔍 Key Insights

Revenue is calculated only from delivered orders, ensuring accuracy

A small group of customers contributes significantly to total revenue

Certain states consistently outperform others in sales

A portion of orders are delivered later than the estimated delivery date

Logistics (freight) represents a notable operational cost

✅ Data Quality Checks Performed

Verified uniqueness of order_id

Checked for NULL values in key order lifecycle timestamps

Validated price and freight values

Identified orphan order items without matching orders

📁 Repository Structure
ecommerce-sql-analysis/
│
├── sql/
│   └── analysis.sql
│
├── database/
│   └── olist.db (or schema description if DB not uploaded)
│
├── dashboards/
│   └── Power BI dashboard (linked below)
│
├── README.md

📈 Dashboard

🔗 Power BI Dashboard:
(Add your Power BI dashboard link here)

📌 Dataset

Public E-Commerce Dataset (Olist)

Data includes customer details, orders, products, and logistics information

🚀 Learnings

Hands-on experience with real-world SQL analysis

Writing complex joins, CTEs, and aggregations

Translating business questions into SQL queries

Importance of data validation before analysis

📬 Contact

If you’d like to discuss this project or provide feedback, feel free to connect!
