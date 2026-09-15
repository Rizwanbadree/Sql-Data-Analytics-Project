# SQL Data Analytics Project
A SQL Server data analytics project focused on exploring sales data, identifying business insights, performing advanced analytics, and creating reusable customer and product reports.
## Project Overview
This project demonstrates an end-to-end SQL data analytics workflow using a sales data warehouse.
The analysis starts with exploratory data analysis (EDA) and progresses into advanced analytics such as:
- Database exploration
- Dimension exploration
- Date range analysis
- Key business metrics
- Magnitude analysis
- Ranking analysis
- Change-over-time analysis
- Cumulative analysis
- Performance analysis
- Data segmentation
- Part-to-whole analysis
- Customer reporting
- Product reporting
## Project Roadmap
![SQL Data Analytics Project Roadmap](./docs/Project%20Roadmap.png)
The project follows two major analytical stages:
### 1. Exploratory Data Analysis (EDA)
The EDA stage focuses on understanding the database, dimensions, dates, key metrics, distributions, and rankings.
### 2. Advanced Analytics
The advanced analytics stage focuses on trends, cumulative performance, year-over-year analysis, segmentation, contribution analysis, and reporting.
---
## Database Structure
The project uses a simple sales data warehouse containing:
### Dimension Tables
- `gold.dim_customers`
- `gold.dim_products`
### Fact Table
- `gold.fact_sales`
The fact table contains sales transactions and connects to customer and product dimensions.
---
## SQL Analysis Scripts
### Exploratory Data Analysis
| `01_database_exploration.sql` | Database and table structure |
| `02_dimensions_exploration.sql` | Customers, countries, categories and products |
| `03_date_range_exploration.sql` | Date and historical range analysis |
| `04_measures_exploration.sql` | Key business metrics |
| `05_magnitude_analysis.sql` | Distribution and magnitude analysis |
| `06_ranking_analysis.sql` | Top and bottom performers |
### Advanced Analytics
| `07_change_over_time_analysis.sql` | Sales trends over time |
| `08_cumulative_analysis.sql` | Running totals and moving averages |
| `09_performance_analysis.sql` | Product performance and YoY analysis |
| `10_data_segmentation.sql` | Customer and product segmentation |
| `11_part_to_whole_analysis.sql` | Category contribution to total sales |
| `12_report_customers.sql` | Customer analytical report |
| `13_report_products.sql` | Product analytical report |
---
## Key SQL Concepts Used
This project demonstrates practical SQL Server techniques including:
- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `JOIN`
- `LEFT JOIN`
- `DISTINCT`
- `CASE`
- `CTE`
- Aggregate functions
- `SUM()`
- `COUNT()`
- `AVG()`
- `MIN()`
- `MAX()`
- `DATEDIFF()`
- `DATEPART()`
- `DATETRUNC()`
- `FORMAT()`
- Window functions
- `RANK()`
- `LAG()`
- `SUM() OVER()`
- `AVG() OVER()`
- Customer segmentation
- Product segmentation
- SQL Views
---
## Business Questions Answered
The project explores questions such as:
- How many customers and products exist?
- Which countries have the most customers?
- What is the total sales revenue?
- What is the average selling price?
- Which product categories generate the most revenue?
- Which products are the top performers?
- Which products have the lowest sales?
- Which customers generate the most revenue?
- How do sales change over time?
- What are the yearly product performance trends?
- Which customers belong to VIP, Regular, or New segments?
- What percentage of total sales comes from each category?
- Which products are high, medium, or low performers?
---
## Customer Report
The customer report provides customer-level analytical metrics including:
- Customer name
- Age
- Age group
- Customer segment
- Last order date
- Recency
- Total orders
- Total sales
- Total quantity purchased
- Total products purchased
- Customer lifespan
- Average order value
- Average monthly spend
### Customer Segments
Customers are classified into:
- VIP
- Regular
- New
---
## Product Report
The product report provides product-level analytical metrics including:
- Product name
- Category
- Subcategory
- Product cost
- Last sale date
- Recency
- Product segment
- Product lifespan
- Total orders
- Total sales
- Total quantity sold
- Total customers
- Average selling price
- Average order revenue
- Average monthly revenue
### Product Segments
Products are classified into:
- High-Performer
- Mid-Range
- Low-Performer
---
## Tools & Technologies
- Microsoft SQL Server
- SQL
- Git
- GitHub
---



