# SQL Data Analytics Project

## Overview

A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more.  
This repository contains SQL queries designed to help data analysts and BI professionals quickly explore, segment, and analyze data within a relational database. Each script focuses on a specific analytical theme and demonstrates best practices for SQL queries.

---

## Purpose

This project focuses on analyzing business data using SQL, applied to sales, customers, and product performance. It includes ready-to-use reports, KPIs,cumulative analysis.

---

## Included Reports

### 1. Product Report 
File: `scripts/product_report.sql`

**Includes:**
- Product details: name, category, subcategory, cost
- Metrics:
  - Total sales
  - Total quantity sold
  - Total number of orders
  - Unique customers
  - Product lifespan (in months)
  - Recency (months since last sale)
- KPIs:
  - Average Order Revenue (AOR)
  - Average Monthly Revenue
  - Performance Segmentation:
  - High / Mid / Low Performer

---

### 2. Customer Report  
File: `scripts/customer_report.sql`

**Includes:**
- Customer profiles and purchasing behavior
- Metrics:
  - Total spending
  - Total number of orders
  - Customer lifespan
- KPIs:
  - Recency
  - Average Monthly Spending
- Segmentation:
  - VIP / Regular / New
  - Age group segmentation

---

### 3. Additional Analytics  
Files: `segmentation.sql`, `cumulative.sql`, etc.

**Includes:**
- Cumulative sales and running totals
- Year-over-year comparisons
- Moving averages
- Category-level contributions to total revenue

---

## Data Sources

- `gold.fact_sales`: Sales transactions
- `gold.dim_products`: Product attributes
- `gold.dim_customers`: Customer attributes

---

## Requirements

- Execution environment: SQL SERVER
- Optional: Tableau for data visualization

---

## Next Steps

- Add Tableau dashboards under `/tableau`
- Include documentation in `/docs/`
- Create materialized views for performance optimization
