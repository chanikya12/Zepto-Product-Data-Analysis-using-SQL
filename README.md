# Zepto-Product-Data-Analysis-using-SQL
This project focuses on performing data cleaning, transformation, and business analysis on the Zepto Product Dataset sourced from Kaggle.  The goal was to extract meaningful business insights related to pricing, discounts, stock availability, and revenue contribution using SQL.
🗂 Dataset Information

Source: Kaggle

Domain: E-commerce / Retail

Database: MySQL

Table Used: zepto_v2

Key Columns:

Product Name

Category

MRP

Discount Percent

Discounted Selling Price

Available Quantity

Weight (in grams)

Stock Status

Quantity

🧹 Data Cleaning & Preparation

✔ Checked total record count
✔ Identified NULL values in critical columns
✔ Removed invalid pricing records (MRP = 0)
✔ Converted prices from paise to rupees
✔ Disabled safe updates for controlled data modification

📊 Business Analysis Performed
🔹 Stock Analysis

Analyzed in-stock vs out-of-stock products

Identified high-value unavailable products

🔹 Revenue Analysis

Calculated category-wise total revenue

Measured inventory weight by category

🔹 Discount Analysis

Found top discounted products

Calculated average discount per category

Identified high-MRP low-discount products

🔹 Pricing Optimization

Computed price per gram

Segmented products into Low / Medium / Bulk categories

📈 Key Insights

Certain categories contribute significantly more revenue

Some premium products have very low discounts

Weight-based pricing shows clear cost efficiency variations

Stock availability impacts revenue potential

🛠 Skills Used

SQL (SELECT, WHERE, GROUP BY, ORDER BY)

Aggregate Functions

CASE Statements

Data Cleaning

Revenue & Pricing Analysis

Business Insight Generation

🚀 Project Outcome

This project strengthened my ability to:

Perform real-world data cleaning

Translate raw data into business insights

Write optimized SQL queries

Think analytically like a Data Analyst

📌 Future Improvements

Build Power BI dashboard on this dataset

Create revenue prediction model

Perform advanced window function analysis

Automate data pipeline using Python
