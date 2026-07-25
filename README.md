
# 📊 Sales Analysis using SQL & Power BI

A complete end-to-end Business Intelligence project demonstrating how raw sales data can be transformed into meaningful business insights using **SQL Server** and **Microsoft Power BI**.

This project follows a real-world data analytics workflow including data cleaning, data modeling, KPI creation, dashboard development, and business insights generation.

---

# 🚀 Project Overview

The objective of this project is to analyze sales performance by leveraging SQL for data preparation and Power BI for interactive dashboard development.

The project includes:

- Data Cleaning using SQL
- Data Transformation
- Star Schema Data Modeling
- DAX Measures
- Interactive Dashboard
- Business KPI Analysis
- Sales Performance Reporting

---

# 🛠 Technologies Used

| Tool | Purpose |
|------|----------|
| SQL Server | Data Cleaning & Transformation |
| T-SQL | Querying & Data Preparation |
| Microsoft Power BI | Dashboard Development |
| DAX | KPI Calculations |
| Excel | Budget Data |
| CSV | Dimension & Fact Data |

---

# 📂 Project Structure

```
SalesAnalysis_SQL_PowerBI
│
├── README.md
│
├── Business Documents
│   ├── Business Demand Overview & User Stories.docx
│   └── Example Business Request.docx
│
├── SQL Scripts
│   ├── DIM_Calendar_Clean.sql
│   ├── DIM_Customer_Clean.sql
│   ├── DIM_Product_Clean.sql
│   └── FACT_InternetSales_Clean.sql
│
├── Data
│   ├── DIM_Calendar_Export.csv
│   ├── DIM_Customer_Export.csv
│   ├── DIM_Product_Export.csv
│   ├── FACT_InternetSales_Export.csv
│   └── SalesBudget.xlsx
│
├── Power BI
│   ├── Sales Report.pbix
│   └── Sales Report.pdf
│
└── Images
    ├── Dashboard.png
    └── DataModel.png
```

---

# 📋 Business Requirements

The business wants to answer the following questions:

- What are the overall sales trends?
- Which products generate the highest revenue?
- Which customers contribute the most sales?
- Which regions perform the best?
- How do sales compare against budget?
- Which products require business attention?

---

# 🗄 Data Warehouse Schema

The project uses a **Star Schema** consisting of:

### Fact Table

- FACT_InternetSales

### Dimension Tables

- DIM_Calendar
- DIM_Customer
- DIM_Product

This schema improves reporting performance and simplifies Power BI relationships.

---

# 🧹 SQL Data Cleaning

The SQL scripts perform:

- Removing unnecessary columns
- Renaming columns
- Formatting dates
- Handling NULL values
- Creating business-friendly fields
- Data filtering
- Data transformation
- Exporting cleaned datasets

SQL concepts used:

- SELECT
- WHERE
- ORDER BY
- CASE
- ISNULL
- LEFT JOIN
- INNER JOIN
- CAST
- CONVERT
- CONCAT

---

# 📈 Power BI Dashboard Features

The dashboard includes:

- Executive Sales Summary
- KPI Cards
- Sales Trend Analysis
- Customer Analysis
- Product Analysis
- Geographic Sales Analysis
- Budget vs Actual Sales
- Top 10 Products
- Top Customers
- Monthly Sales Performance
- Interactive Filters
- Drill-through Pages
- Dynamic Tooltips

---
