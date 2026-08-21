## SQL Data Analytics Project

This project showcases my SQL data analytics practice as a fresher, focused on turning raw sales data into business-ready insights using dimensional modeling, reporting views, and exploratory analysis queries.

## Project Objectives
- Build a small analytics-ready data warehouse in SQL Server.
- Analyze customer and product performance using SQL.
- Create reusable report views for decision-making.
- Practice core data analyst skills: segmentation, trends, ranking, and performance analysis.

## Tech Stack
- **Database:** Microsoft SQL Server (T-SQL)
- **Data Source:** CSV flat files
- **Artifacts:** SQL scripts, exploratory analysis, customer/product reporting views

## Repository Structure
- `/scripts` – End-to-end SQL workflow from database setup to reports
- `/datasets/flat-files` – Input CSV files
- `/docs` – Supporting project roadmap and notes

## Script Flow
Run scripts in this order:
1. `00_init_database.sql` – Creates database/schema/tables and loads data
2. `01` to `11` scripts – Exploration and analytical pattern analysis
3. `12_report_customers.sql` – Creates customer KPI report view
4. `13_report_products.sql` – Creates product KPI report view

## How to Run
1. Open SQL Server Management Studio (or equivalent SQL Server client).
2. Update file paths in `00_init_database.sql` `BULK INSERT` statements to match your local dataset location.
3. Execute `scripts/00_init_database.sql`.
4. Execute remaining scripts in sequence.
5. Query final report views:
   - `SELECT * FROM gold.report_customers;`
   - `SELECT * FROM gold.report_products;`

## Key Analysis Topics Covered
- Database and schema setup
- Data exploration and profiling
- Date range and measures analysis
- Magnitude and ranking analysis
- Change-over-time and cumulative analysis
- Performance and segmentation analysis
- Part-to-whole contribution analysis

## Learning Outcome
Through this project, I strengthened practical SQL skills in data preparation, analytical querying, and report creation with a business-focused approach.
