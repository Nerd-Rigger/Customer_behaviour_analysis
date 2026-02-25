📊 Data Analytics Project
1. Overview

This project demonstrates an end-to-end data analytics workflow — from raw dataset processing to business insights and dashboard reporting.

The objective was to analyze customer purchasing behavior, clean and transform data, run structured SQL queries, and present insights using an interactive Power BI dashboard and executive presentation.

This project highlights practical skills in:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

SQL querying

Data visualization

Business reporting
<img width="4872" height="2656" alt="image" src="https://github.com/user-attachments/assets/1d8b1c57-ab20-47a6-bbc2-cd62c60839e1" />


2. Dataset

The dataset contains customer transaction data including:

Customer ID

Product purchased

Category

Purchase frequency

Discount applied

Previous purchases

Other transactional attributes

The dataset was loaded into Python for analysis and later imported into MySQL Server for structured querying.

3. Tools & Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

MySQL Server

SQL (Window Functions, Aggregations, CTEs)

Power BI

Gamma (for presentation slides)

4. Project Workflow / Steps
🔹 Step 1: Data Loading (Python)

Imported dataset into Jupyter Notebook

Inspected structure and data types

Identified missing and inconsistent values

🔹 Step 2: Data Cleaning

Handled missing values

Removed duplicates

Standardized categorical values

Corrected data types

Created derived columns when necessary

🔹 Step 3: Exploratory Data Analysis (EDA)

Analyzed purchase distribution

Identified most purchased products

Calculated discount rates

Segmented customers (New, Returning, Loyal)

Performed category-wise analysis

🔹 Step 4: SQL Analysis (MySQL Server)

Dataset was imported into MySQL for advanced querying:

Aggregations (COUNT, SUM, AVG)

Customer segmentation using CASE statements

CTEs (Common Table Expressions)

Window functions (ROW_NUMBER)

Top products per category

Discount impact analysis

🔹 Step 5: Power BI Dashboard

Built an interactive dashboard including:

Sales by category

Top purchased products

Customer segmentation breakdown

Discount analysis

Key performance indicators (KPIs)

🔹 Step 6: Reporting & Presentation

Created a structured analytical report

Designed executive presentation using Gamma

Summarized insights and business recommendations

5. Dashboard

The Power BI dashboard includes:

Interactive filters

Category-wise performance visuals

Top 3 products per category

Customer segmentation distribution

Discount rate insights

The dashboard provides decision-making insights in a visual and easy-to-understand format.

6. Key Results & Insights

Identified top-performing products within each category

Discovered customer purchase behavior patterns

Segmented customers into actionable groups

Measured the impact of discounts on purchase frequency

Provided recommendations to optimize sales strategy

7. How to Run This Project
🔹 Python Analysis

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn pymysql sqlalchemy

Open the Jupyter Notebook

Run all cells sequentially

🔹 MySQL Setup

Install MySQL Server

Create database

Import dataset into MySQL

Run provided SQL queries

🔹 Power BI

Open the .pbix file

Ensure MySQL connection is active

Refresh data if required

🎯 Project Objective

This project demonstrates practical application of:

Data cleaning and preparation

SQL querying and window functions

Business intelligence visualization

End-to-end analytics workflow

It reflects real-world data analyst responsibilities from raw data to actionable business insights.
