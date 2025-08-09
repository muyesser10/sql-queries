# SQL Queries - FLO Customer Analysis

This repository contains SQL queries performed on a sample dataset called **FLO** for customer analysis.  
The aim is to practice SQL skills by extracting meaningful business insights from customer data.

# Contents

- **Database and Table Creation**  
  - Creation of the `CUSTOMERS` database  
  - Definition of the `FLO` table and its fields (customer info, order channels, date fields, order counts, revenue, etc.)  

- **Analysis Queries**
  1. Count of distinct customers  
  2. Total order count and revenue calculation  
  3. Average revenue per order  
  4. Total revenue and order count by last purchase channel  
  5. Revenue breakdown by store type  
  6. Order counts by first order year  
  7. Average revenue by last purchase channel  
  8. Most popular category in the last 12 months  
  9. Most preferred store type  
  10. Most popular category and revenue by purchase channel  
  11. Top spending customer with average revenue and purchase frequency  
  12. Analysis of the top 100 customers by revenue  
  13. Top customer by last purchase channel  
  14. Customers with the most recent purchases  

- **Bonus Queries**  
  - Parsing data using `string_split` and `CROSS APPLY`  
  - Ranking using `ROW_NUMBER()`

## 🛠 Technologies Used

- **SQL Server** (T-SQL syntax)  
- SQL functions and clauses such as:  
  - `GROUP BY`, `ORDER BY`  
  - Aggregations: `SUM()`, `COUNT()`, `ROUND()`  
  - `DISTINCT`, `TOP`, `ROW_NUMBER()`  
  - `string_split`  
  - Date functions: `DATEDIFF()`, `YEAR()`  
  - `CROSS APPLY` and subqueries

## 📈 Purpose

This project aims to improve SQL skills, practice extracting actionable business insights from datasets, and learn query optimization techniques.

