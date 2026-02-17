# Retail ETL Pipeline Project

This project demonstrates a complete end-to-end ETL (Extract, Transform, Load) pipeline using Python and SQL, with a documented Power BI dashboard design. It is intended as a portfolio-ready example for BI and Data Engineering roles.

---

## Project Overview

The pipeline processes raw retail sales data from a CSV file, cleans and enriches the data, loads it into a SQL database, and supports analytics queries and BI reporting.

This project focuses on:
- Clean ETL structure
- Readable, modular Python code
- SQL analytics readiness
- Clear documentation for recruiters and reviewers

---

## Project Structure



## ETL Workflow

### 1. Extract
- Reads raw sales data from a CSV file
- Uses Pandas to load data into a DataFrame

### 2. Transform
- Cleans and formats date fields
- Calculates revenue (quantity × price)
- Prepares data for analytics and reporting

### 3. Load
- Loads transformed data into a SQLite database
- Creates a reusable `sales` table for analysis

---


## How to Run the Pipeline

From the root project folder:

```bash
python etl/extract.py
python etl/transform.py
python etl/load.py



###After running load.py, a SQLite database (retail.db) will be created containing the cleaned sales data.

SQL Analytics
The sql/analytics_queries.sql file includes example queries such as:

Total revenue by category
Units sold by region

These queries support BI dashboards and ad-hoc analysis.

Power BI Dashboard
A mock Power BI dashboard design is documented in:
dashboard/dashboard_description.txt

It includes:

Executive KPIs
Product performance
Regional sales analysis
Daily sales exploration

Skills Demonstrated

Python ETL development
Data transformation and enrichment
SQL schema design and analytics
BI dashboard planning
GitHub project organization and documentation


Barbara 
Created as a portfolio project to demonstrate practical data engineering and BI skills.
