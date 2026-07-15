# Mobile-Sales-Dashboard
I wanted to improve my Power BI skills by building an end-to-end business dashboard. I selected a mobile sales dataset because it contains multiple business dimensions like products, customers, cities, payment methods, and dates, making it suitable for sales analysis. I used a publicly available dataset from a YouTube tutorial for learning purposes.

My task was to clean the raw data, prepare it for analysis, create an interactive Power BI dashboard, and provide meaningful business insights using KPIs, charts, filters, and time intelligence calculations.

Step 1 - Data Import

I imported the sales dataset into Power BI.

Step 2 - Power Query

In Power Query, I cleaned and transformed the data by checking data types, removing unnecessary data, and preparing the dataset for analysis.

I also created custom date-related columns in Power Query such as Year, Quarter, Month Name, Month Number, and Day Name. These columns helped me perform time intelligence analysis and create Month-to-Date and Same Period Last Year reports.

Step 3 - Data Modeling

I created a separate Calendar Table and established a relationship between the Calendar table and the Sales table using the Date field. This allowed me to perform accurate time intelligence calculations.

Step 4 - DAX Measures

I created DAX measures for the main KPIs.

KPI 1

Total Sales: Calculates the total revenue generated from mobile sales.

KPI 2

Total Quantity: Calculates the total number of mobile units sold.

KPI 3

Total Transactions: Counts the total number of sales transactions.

KPI 4

Average Price: Calculates the average selling price of mobiles.

Step 5 - Dashboard Design

I designed three interactive dashboard pages.

Dashboard Page: Main dashboard provides an overall business summary.

It includes: 
Total Sales KPI
Total Quantity KPI
Total Transactions KPI
Average Price KPI
Sales by City
Monthly Sales Trend
Sales by Brand
Sales by Mobile Model
Payment Method Distribution
Rating Analysis

Interactive slicers: 
Brand
Mobile Model
Payment Method
MTD Report

I created an MTD (Month-to-Date) report to monitor cumulative sales performance throughout the selected month. It helps business users track daily sales progress and compare current performance over time.

Same Period Last Year

I developed a Same Period Last Year report using DAX Time Intelligence functions. This allows users to compare current year sales with the corresponding period of the previous year at yearly, quarterly, and monthly levels.

Filters

I also added interactive slicers and cross-filtering so users can analyze sales by brand, payment method, mobile model, month, and year.

The final dashboard provides an interactive overview of mobile sales performance. It enables users to monitor KPIs, identify top-performing brands and cities, analyze customer purchasing behavior, compare current sales with the previous year, and make data-driven business decisions more efficiently.
