# devlab-internship-week2-task3
Customer purchasing behavior, revenue, sales trends, return analysis, and country-level insights using Python, Pandas, and Matplotlib.
# Online Retail Sales Analysis

## Project Overview
This project analyzes an online retail dataset using Python. The analysis focuses on customer purchasing behavior, revenue generation, country-level performance, return rates, and monthly sales trends through data cleaning, aggregation, and visualization.

## Dataset
https://www.kaggle.com/datasets/carrie1/ecommerce-data

## Objectives
- Inspect the dataset
- Separate cancelled orders
- Handle missing values
- Create a revenue column
- Analyze customer purchasing behavior
- Compare country performance
- Analyze monthly revenue trends
- Identify top-selling products
- Calculate return rates by country

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Tasks
1. Loaded and inspected the dataset.
2. Separated cancelled orders using the InvoiceNo column.
3. Removed rows with missing CustomerID values for customer-level analysis.
4. Filtered negative Quantity values while keeping them for return analysis.
5. Created a Revenue column using Quantity × UnitPrice.
6. Analyzed customer revenue, total orders, and average order value.
7. Compared countries by revenue, order count, and revenue share.
8. Analyzed monthly revenue trends.
9. Identified the top 20 best-selling products.
10. Calculated return rates by country.

## Visualizations
- Monthly Revenue Trend (Line Chart)
- Top 10 Countries by Revenue (Bar Chart)
- Top 20 Products by Quantity Sold (Horizontal Bar Chart)
- Return Rate by Country (Bar Chart)

## Bonus Features
- Top 10 Customers by Revenue and their Monthly Spending Trend
- Average Basket Size per Country

## Business Insights
- High-value customers contribute a significant portion of total revenue.
- A few countries account for most of the company's sales.
- Monthly revenue follows seasonal patterns with noticeable peak periods.
- Top-selling products consistently drive overall sales performance.
- Return rates differ across countries and may indicate opportunities for operational improvements.

