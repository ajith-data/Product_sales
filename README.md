🚀 Product Sales Analysis | Python Data Analytics Project

End-to-End Sales, Customer Behavior & Profitability Analysis using Python

📌 Project Summary

This project performs a complete real-world exploratory data analysis (EDA) on a retail product sales dataset to uncover sales trends, customer behavior, return patterns, and profitability insights. It demonstrates industry-level Data Analyst skills including data cleaning, outlier handling, visualization, and business insight generation.

❓ Problem Statement

Retail organizations generate large volumes of sales data across products, regions, customers, and time periods. However, raw sales data often contains missing values, invalid entries, inconsistent dates, and extreme outliers. These issues make it difficult to identify top-performing products, profitable customers, sales trends, and business risks.

This project aims to clean, preprocess, analyze, and visualize sales data to transform raw transactional data into meaningful, data-driven business insights.

🧰 Tech Stack

Python
Pandas – Data manipulation and analysis

Matplotlib – Data visualization

Seaborn – Statistical and distribution plots

Excel (openpyxl) – Data source

📊 Dataset Overview
The dataset contains retail sales transactions with the following key attributes:

Product, Region, StoreLocation,
CustomerName, CustomerType,
Quantity, UnitPrice, Discount, ShippingCost, TotalPrice,
PaymentMethod, Promotion, Returned,
OrderDate, DeliveryDate,
Salesperson

🧠 Concepts Covered (Short & Clear)
🧹 Data Loading & Inspection

Loaded Excel data using Pandas

Inspected structure, data types, and missing values using head() and info()

🧹 Data Cleaning
Removed rows with missing or invalid payment methods

Handled missing promotion values using imputation

Converted date columns into proper datetime format

🕵️ Missing Value Handling

Identified missing values using isna()

Applied smart filling instead of deleting data to avoid information loss

📅 Date Validation

Verified logical consistency where DeliveryDate ≥ OrderDate

Ensured transactional data integrity

📦 Outlier Detection (IQR Method)

Calculated Q1, Q3, and IQR for TotalPrice

Identified extreme values using statistical boundaries

Visualized outliers using boxplots

✂️ Outlier Treatment (Capping)

Applied winsorization (capping) to limit extreme values

Reduced skewness while preserving overall data distribution

🔄 Return Rate Analysis

Calculated percentage of returned orders

Segmented data into returned and non-returned transactions

Used non-returned data for accurate sales analysis

🏆 Product Sales Analysis

Identified top-selling products based on revenue

Compared product-level contribution to total sales

🌍 Region & Store Analysis

Analyzed sales performance across regions and store locations

Identified high-performing and low-performing areas


👨‍💼 Salesperson Performance Analysis

Ranked salespersons based on total sales

Visualized performance using horizontal bar charts

⏳ Time-Series Sales Analysis

Extracted Year and Month from order dates

Analyzed monthly and yearly sales trends

Identified seasonality and peak sales periods

💰 Profitability Analysis

Calculated profit using:

Profit = TotalPrice − (Quantity × UnitPrice)

Identified profitable and low-margin transactions

👥 Customer Behavior Analysis

Identified repeat customers

Analyzed customer type contribution to revenue

Studied payment method preferences

⭐ Loyalty Score (Custom Metric)

Designed a custom loyalty metric to measure customer value:

Loyalty Score = (Order Count × Average Order Value) / (1 + Average Discount)

🚀 Future Enhancements

Power BI / Tableau dashboard

SQL-based implementation

Sales forecasting models

Customer segmentation using machine learning
