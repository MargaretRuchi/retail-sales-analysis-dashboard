# Retail Sales Analysis Dashboard

## Project Overview
This project analyzes retail sales transaction data to uncover revenue trends, top-performing products, customer purchasing patterns, and key business insights. The objective is to transform raw sales data into actionable information that can support strategic business decisions.

Through data cleaning, exploratory data analysis (EDA), feature engineering, and visualization, this project identifies sales drivers and highlights opportunities for business growth.


## Business Problem
Retail businesses generate large volumes of transactional data daily. However, without proper analysis, valuable insights regarding customer behavior, product performance, and revenue trends may remain hidden.

This project aims to answer the following business questions:

* What is the total revenue generated?
* Which products generate the highest sales?
* Which countries contribute the most revenue?
* How do sales fluctuate over time?
* What insights can support business decision-making?


## Dataset Information

**Dataset:** Online Retail Dataset

The dataset contains transactional records from an online retail store and includes information such as:

* Invoice Number
* Product Description
* Quantity Sold
* Unit Price
* Customer ID
* Country
* Invoice Date


## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn


## Project Workflow

### 1. Data Collection

Imported retail sales transaction data into Google Colab for analysis.

### 2. Data Cleaning

* Removed missing values
* Removed invalid transactions
* Handled data inconsistencies
* Converted date fields into proper datetime format

### 3. Feature Engineering

Created additional features including:

* Total Sales
* Month
* Year

### 4. Exploratory Data Analysis

Analyzed:

* Revenue trends
* Product performance
* Country-level sales
* Customer purchasing patterns

### 5. Data Visualization

Developed charts and graphs to communicate key findings effectively.

### 6. Business Insights

Generated recommendations based on observed trends and patterns.

## Key Performance Indicators (KPIs)

The analysis focuses on the following KPIs:

* Total Revenue
* Total Transactions
* Top-Selling Products
* Monthly Revenue Trends
* Country Revenue Distribution

## Visualizations

### Monthly Revenue Trend
### Top Products by Revenue
### Top Countries by Revenue

## Key Findings

* Revenue performance varied significantly across different months.
* A small group of products generated a large proportion of total sales.
* Certain countries contributed the majority of revenue.
* Sales patterns indicated potential seasonal purchasing behavior.

## Business Recommendations

1. Increase inventory levels for high-performing products.
2. Prepare marketing campaigns ahead of peak sales periods.
3. Focus customer retention efforts in high-revenue markets.
4. Monitor underperforming products and optimize inventory allocation.
5. Use historical sales trends to improve demand forecasting.

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Analytics
* Insight Generation
* Reporting and Communication


## Project Structure

retail-sales-analysis/

├── notebook/

│ └── Retail_Sales_Analysis.ipynb

├── visuals/

│ ├── monthly_sales.png

│ ├── top_products.png

│ └── country_sales.png

├── data/

│ ├── raw_data.csv

│ └── cleaned_data.csv

└── README.md

## Conclusion

This project demonstrates the ability to clean, analyze, and visualize retail sales data using Python and Google Colab. The findings provide actionable insights that can support business growth, operational efficiency, and data-driven decision-making.
