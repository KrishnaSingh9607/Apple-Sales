# 🍎 Apple Sales Analysis using SQL & Excel

## 📌 Project Overview

This project analyzes Apple product sales data using **SQL** for database management and querying, and **Microsoft Excel** for data visualization and reporting.

The project demonstrates SQL concepts such as:
- Database design
- Table creation
- Primary & Foreign Keys
- Joins
- Aggregate Functions
- Common Table Expressions (CTEs)
- Window Functions
- Date Functions
- Business Analysis Queries

---

## 🛠️ Technologies Used

- SQL (PostgreSQL)
- Microsoft Excel
- Git & GitHub

---

## 📂 Database Schema

The database consists of the following tables:

### 1. Stores
Contains information about Apple stores.

| Column | Description |
|---------|-------------|
| store_id | Store ID |
| store_name | Store Name |
| city | Store City |
| country | Store Country |

---

### 2. Category
Contains product categories.

| Column | Description |
|---------|-------------|
| category_id | Category ID |
| category_name | Category Name |

---

### 3. Products
Contains Apple product information.

| Column | Description |
|---------|-------------|
| product_id | Product ID |
| product_name | Product Name |
| category_id | Product Category |
| launch_date | Launch Date |
| price | Product Price |

---

### 4. Sales
Contains sales transactions.

| Column | Description |
|---------|-------------|
| sale_id | Sale ID |
| sale_date | Sale Date |
| store_id | Store ID |
| product_id | Product ID |
| quantity | Units Sold |

---

### 5. Warranty
Contains warranty claim information.

| Column | Description |
|---------|-------------|
| claim_id | Claim ID |
| claim_date | Claim Date |
| sale_id | Sale ID |
| repair_status | Warranty Status |

---

# 📊 Business Questions Solved

This project answers several real-world business questions using SQL.

### 1. Count total Apple stores in each country.

### 2. Find total units sold by each store.

### 3. Count total sales made during December 2023.

### 4. Identify stores that never received a warranty claim.

### 5. Calculate the percentage of warranty claims marked as **Warranty Void**.

### 6. Find the Top 5 stores with the highest sales during the last 1 year and 2 months.

### 7. Count unique Apple products sold in the last year.

### 8. Calculate the average retail price for each product category.

### 9. Count warranty claims submitted during 2020.

### 10. Determine the best-selling weekday for every store using SQL Window Functions.

---

# 📈 Excel Dashboard

The Excel dashboard includes visual analysis such as:

- Sales by Store
- Sales by Country
- Product Category Performance
- Monthly Sales Trend
- Warranty Claim Analysis
- Top Selling Products
- KPI Summary

---

# 🧠 SQL Concepts Used

- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- INNER JOIN
- GROUP BY
- ORDER BY
- COUNT()
- SUM()
- AVG()
- ROUND()
- DISTINCT
- CASE WHEN
- DATE & INTERVAL Functions
- EXTRACT()
- Common Table Expressions (CTEs)
- Window Functions (RANK())

---

# 📁 Project Structure

```
Apple-Sales-Analysis/
│
├── SQL/
│   ├── create_tables.sql
│   ├── data_import.sql
│   └── analysis_queries.sql
│
├── Excel/
│   └── Apple_Sales_Dashboard.xlsx
│
├── Dataset/
│   ├── stores.csv
│   ├── products.csv
│   ├── sales.csv
│   ├── category.csv
│   └── warranty.csv
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

# 🚀 Learning Outcomes

Through this project, I practiced:

- Designing a relational database
- Writing optimized SQL queries
- Performing business data analysis
- Working with relational data
- Creating Excel dashboards
- Uploading projects to GitHub

---

# ⭐ Future Improvements

- Build an interactive Power BI Dashboard
- Create a Tableau version
- Add SQL stored procedures
- Optimize complex queries
- Perform predictive sales analysis using Python

---
