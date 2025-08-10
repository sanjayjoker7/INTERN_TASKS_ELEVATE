# Task 4 – SQL for Data Analysis

## 📌 Overview
This project is part of my **Data Analyst Internship** at **Elevate Labs**, focusing on using SQL to extract, clean, and analyze structured data.  
I worked with the **Ecommerce Sales Dataset** to perform queries that provide business insights.

## 🎯 Objectives
- Use **SELECT, WHERE, ORDER BY, GROUP BY** for filtering and sorting data.
- Apply **aggregate functions** like SUM, AVG, COUNT for KPIs.
- Implement **JOINS** to combine related tables.
- Write **subqueries** for advanced filtering.
- Create **views** for reusable insights.
- Learn basic **query optimization** techniques.

## 🛠 Tools & Technologies
- **PostgreSQL 17**
- **pgAdmin 4**
- SQL scripting (`.sql` file)

## 📂 Dataset
**Source:** [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets)  
**Table:** `ecommerce_data`  
**Columns:**
- `InvoiceNo` – Unique invoice number
- `StockCode` – Product code
- `Description` – Product description
- `Quantity` – Number of products sold
- `InvoiceDate` – Date & time of purchase
- `UnitPrice` – Price per unit
- `CustomerID` – Unique customer ID
- `Country` – Customer’s country

## 📜 Queries Implemented
1. **Top 10 Selling Products**
2. **Total Sales by Country**
3. **Monthly Revenue Trend**
4. **Most Frequent Customers**
5. **Average Order Value**
6. **Products with Highest Revenue**
7. **Subquery** – Customers who bought more than 100 items
8. **Join Example** (created `customers` table from raw data)
9. **View** – `monthly_sales` for quick trend analysis
10. **Filtered Insights** – Top countries excluding the UK


## 🚀 How to Run
1. Install **PostgreSQL** & **pgAdmin 4**.
2. Create a new database (e.g., `task`).
3. Import `ecommerce_data.csv` into PostgreSQL.
4. Run the queries in `queries.sql` using pgAdmin Query Tool.

## 📈 Key Insights
- UK customers accounted for **over 80%** of sales.
- The top-selling product generated over **£20,000** in revenue.
- December saw a **spike in sales**, indicating holiday demand.
- A small number of repeat customers contribute a significant portion of total sales.

## 📌 Learning Outcomes
- Enhanced skills in **SQL data manipulation & analysis**.
- Learned to create **views** and write **subqueries** for business problems.
- Improved understanding of **data-driven decision-making**.


