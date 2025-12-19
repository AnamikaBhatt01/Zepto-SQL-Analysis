# Zepto-SQL-Analysis
  Zepto SQL Data Analysis Project demonstrates relational database design, SQL querying, and business analytics using the Zepto Inventory Dataset. Includes sales, inventory, and category insights, ER diagrams, and SQL outputs ready for Excel dashboards. Ideal for portfolios and analytics showcase.   
🛒 Zepto SQL Data Analysis Project

📌 Project Overview

This project is an end-to-end SQL-based data analysis case study built using the Zepto Inventory Dataset. The goal of the project is to demonstrate strong command over SQL querying, database design, business analytics, and data storytelling, similar to real-world retail / quick-commerce analytics.

The project covers data modeling, data cleaning, analytical SQL queries, inventory insights, sales analysis, and dashboard-ready outputs, making it suitable for portfolio, interviews, and LinkedIn/GitHub showcasing.
🎯 Objectives

Design a clean relational database schema for Zepto-like operations

Perform sales, revenue, and inventory analysis using SQL

Generate business-driven insights without time-based columns

Prepare outputs that can be directly used for Excel dashboards & visualizations

Follow industry-level GitHub project structure

🧩 Dataset

Source: Kaggle – Zepto Inventory Dataset

Domain: Quick Commerce / Retail Analytics

Data Type: CSV files imported into SQL


Key Entities in Dataset

Products

Categories

Inventory

Pricing

Orders / Sales (derived)

🗄️ Database Design

The project follows normalized relational database principles.

Tables Designed

categories

products

inventory

pricing

sales (derived / analytical)


Key Concepts Used

Primary Keys & Foreign Keys

One-to-Many relationships

Data normalization

Business-ready schema design


📌 A clean, bold ER Diagram (PostgreSQL-style) is included in the project for visualization and explanation.


---

⚙️ Tech Stack

Database: MySQL / PostgreSQL (SQL-compliant)

IDE: MySQL Workbench / VS Code

Data Source: CSV

Visualization: Excel Dashboard

Version Control: Git & GitHub

🛠️ Project Workflow

1️⃣ Data Import & Setup

CSV files loaded into SQL using LOAD DATA INFILE

Handled local infile configuration issues

Verified data integrity after import


2️⃣ Data Cleaning

Checked for NULL values

Removed duplicates

Standardized category and product naming


3️⃣ SQL Analysis Performed

📊 Sales Analysis

Total sales revenue

Category-wise revenue contribution

Product-wise sales ranking

High-revenue vs low-revenue products


📦 Inventory Analysis

Stock availability insights

Overstocked and understocked products

Inventory value by category

Low inventory risk identification


🧮 Business Insights (Without Date Columns)

Since the dataset does not contain date columns, insights were derived using:

Aggregate functions

Category and product distribution

Revenue contribution patterns

Inventory-to-sales relationship


> This mirrors real-world scenarios where time-based data may be missing or incomplete.




---

📈 Excel Dashboard

SQL outputs are structured to be directly consumable in Excel.

Dashboard Metrics

Grand Total Revenue

Category-wise Sales Distribution

Product-wise Revenue

Inventory Value Breakdown


📌 Pivot Tables and charts were created using SQL query outputs.


---

🧠 Key Insights Generated

Which categories drive maximum revenue

Products contributing disproportionately to revenue

Inventory imbalance across categories

Business risks due to low-stock high-demand products



---

📁 Repository Structure

zepto-sql-data-analysis-project/
│
├── data/
│   ├── raw_csv_files/
│   └── cleaned_data/
│
├── sql/
│   ├── schema.sql
│   ├── data_import.sql
│   ├── cleaning_queries.sql
│   ├── analysis_queries.sql
│   └── business_insights.sql
│
├── er_diagram/
│   └── zepto_er_diagram.png
│
├── excel_dashboard/
│   └── zepto_dashboard.xlsx
│
