# Retail Sales Exploratory Data Analysis (EDA)

An exploratory data analysis of retail sales transactions using Python to uncover patterns, customer behavior, and business insights.

## Project Overview
This project analyzes a retail sales dataset containing 1,000 transaction records to understand sales trends, customer demographics, and product performance.

## Dataset Structure (`retail_sales_dataset.csv`)
The dataset consists of 1,000 rows and 9 columns:
- **Transaction ID**: Unique identifier for each transaction.
- **Date**: Date when the transaction occurred.
- **Customer ID**: Unique identifier for the customer.
- **Gender**: Gender of the customer (Male / Female).
- **Age**: Age of the customer.
- **Product Category**: Category of the product purchased (Beauty, Clothing, Electronics).
- **Quantity**: Number of units bought per transaction.
- **Price per Unit**: Cost per individual unit.
- **Total Amount**: Total transaction value (Quantity × Price per Unit).

## Tech Stack
- Python
- Pandas & NumPy (Data processing)
- Matplotlib & Seaborn (Visualisation)
- Jupyter Notebook

## Key Steps & Analysis
1. **Data Inspection**: Checked data types, missing values, and dataset shape.
2. **Descriptive Statistics**: Calculated mean, median, mode, and standard deviation, along with an IQR outlier analysis.
3. **Time Series Analysis**: Evaluated monthly and quarterly sales trends.
4. **Customer Demographics**: Analyzed customer age group distribution and gender breakdown.
5. **Product Performance**: Identified top-selling product categories and revenue generation.
6. **Correlation Heatmap**: Examined statistical relationships between numerical variables.

## Key Recommendations
- Focus inventory and supply chain scaling on high-revenue product categories.
- Maintain broad marketing strategies to appeal to the well-balanced customer demographics.
- Implement cross-selling bundles for high-frequency purchase categories to boost average order values.
