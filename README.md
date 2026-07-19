# SQL Sales Analysis Project

## Project Overview

This project analyzes a retail sales dataset using MySQL. The objective is to extract meaningful business insights through SQL queries involving filtering, aggregation, sorting, grouping, and data analysis.

---

## Dataset

- Dataset: Superstore Sales
- Format: CSV
- Database: MySQL
- Tool: MySQL Workbench

---

## Objectives

- Import CSV into MySQL
- Clean and verify data
- Perform SQL analysis
- Generate business insights
- Prepare results for visualization

---

## Skills Demonstrated

- Database Creation
- Table Design
- Data Import
- Data Validation
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- Aggregate Functions
- CASE Statements
- Date Functions
- Subqueries
- Common Table Expressions (CTEs)
- Views
- Indexes
- Query Optimization

---

## Sample SQL Query

```sql
SELECT
Category,
ROUND(SUM(Sales),2) AS TotalSales
FROM superstore
GROUP BY Category
ORDER BY TotalSales DESC;
```

---

## Key Insights

- Identified top-performing product categories.
- Compared sales across different regions.
- Calculated total, average, maximum, and minimum sales.
- Ranked categories based on revenue.

---

---

## Project Structure

```
SQL-Sales-Analysis
│
├── Dataset
├── SQL Queries
├── Screenshots
└── README.md
```

---

## Author

**Prudhvi Surla**

Aspiring Data Analyst

Skills:
- SQL
- MySQL
- Power BI
- Python
- Excel

---
