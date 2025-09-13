**📊 AMAZON SALES ANALYSIS (SQL + POWER BI)**

**PROJECT OVERVIEW**
This project focuses on analyzing Amazon sales data using SQL for data exploration and Power BI for visualization.
The goal is to uncover insights on sales performance, customer behavior, product profitability, and regional trends to support data-driven decision making.

**TOOLS & TECHNOLOGIES**

SQL Server / MySQL → Data cleaning, transformation, exploratory queries
Power BI → Interactive dashboards & business storytelling
Excel / CSV → Raw data source

**SQL ANALYSIS PERFORMED
**
Sales by category, sub-category, and product
Revenue and profit trends (daily, monthly, yearly)
Top 10 most profitable and least profitable products
Regional sales performance (state/city level)
Customer segmentation (repeat vs one-time buyers)

Example Query:

SELECT Category, SUM(Sales) AS TotalSales, SUM(Profit) AS TotalProfit
FROM AmazonSales
GROUP BY Category
ORDER BY TotalSales DESC;

**
POWER BI DASHBOARD**

The dashboard contains multiple interactive pages:
Executive Summary
KPIs: Total Sales, Total Profit, Avg. Order Value, Number of Orders
Sales Trends
Monthly sales and profit trend lines
Filters by Year, Category, and Region
Product Performance
Top 10 products by sales and profit
Category-wise contribution
Customer Insights
Customer segmentation (new vs repeat buyers)
Average spend per customer
Regional Analysis
Sales by state/city
Heatmap of top-performing regions

**KEY INSIGHTS**

Top 3 product categories contributed nearly 60% of total revenue
Seasonal peaks observed in Q4 (holiday season)
About 20% of customers contribute ~70% of profits
Metropolitan cities emerged as highest revenue generators

**PROJECT FILES**

Amazon_Sales_Analysis.sql → SQL scripts for data analysis
Amazon_Sales_Dashboard.pbix → Power BI dashboard file
Amazon_Sales_Data.csv → Raw dataset
**
HOW TO USE**

Import the dataset into SQL Server/MySQL.
Run queries from Amazon_Sales_Analysis.sql.
Open the Power BI file Amazon_Sales_Dashboard.pbix and connect it to the SQL/CSV source.
Explore and interact with the dashboard.
**
FUTURE IMPROVEMENTS**

Add sales forecasting for trend prediction
Customer lifetime value (CLV) analysis
Automate data refresh in Power BI Service
