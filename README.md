# Sales Trend Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(EDA))
- [Data Analysis](#data-analysis)
- [Results/Findings](##results/findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
  
### Project Overview
This sales trend data analysis aims to understand what drives the success of retail stores at Walmart. By analyzing weekly sales data of various stores at Walmart, under various conditions (seasons - Holiday and Non-Holiday). We seek to identify trends, make detailed data-driven recommendations, and gain a deeper understanding of each retail store's weekly performance.

<img width="1617" height="556" alt="Screenshot 2025-10-19 002121" src="https://github.com/user-attachments/assets/228a9a1d-8ee6-4541-b9b8-a42d7ce65eb9" />

### Data Source
Sales_Data: The primary dataset used in this analysis is the "Walmart_Sales.csv" file, containing detail report of weekely sales made by each retail store on holiday seasons and non-holiday seasons.
Source : Kaggles Open Source

### Tools
- Excel: Used for data cleaning, analysis and visualization.

### Data Cleaning/Preparation
Steps Taken:
- Checked for missing values — none found
- Removed inconsistent decimal formats in Weekly_Sales
- Verified date types (converted all to date format)
- Removed duplicates (none found)
- Formatted numeric fields (currency for Weekly_Sales, 2 decimals for Fuel_Price)

### Exploratory Data Analysis (EDA)
During the exploratory data analysis, I explored the weekly sales data to answer the following questions:
1. How do holiday weeks affect Walmart’s weekly sales?
2. Which store has the highest average weekly sales?
3. Do fuel prices correlate with weekly sales?

### Data Analysis
In the excel data analysis, I made use of pivot tables.

### Results/Findings
- Holiday periods boost weekly sales by ~15–20%.
- Store 20 and Store 4 outperform consistently.
- Rising fuel prices may reduce spending power, slightly lowering weekly sales.

### Recommendation
From my findings after the data analysis, I recommend Walmart can strengthen performance by:
1. Leveraging predictive demand planning before holidays.
2. Developing regional pricing and promotion strategies tied to local store performance.
3. Tracking macroeconomic indicators like fuel prices to forecast spending behavior.

### Limitations
- Dataset limited to 2010–2012 (no recent data).
- No store-level demographic or marketing spend data.
- Inflation and regional economic variations not fully captured.
