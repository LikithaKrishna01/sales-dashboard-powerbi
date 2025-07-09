 E-Commerce Sales Dashboard – Power BI

 Overview
This Power BI dashboard analyzes sales performance data from a fictional e-commerce company. It provides insights into total sales, profit, orders, product performance, and regional trends.

# Dataset Summary
The dataset contains the following key columns:

OrderID – Unique identifier for each order

Date – Transaction date

Region – Sales region

Product – Product name

TotalPrice – Gross sales value

Discount – Discount applied

ShippingCost – Cost of delivery

# Key Features
 KPI Cards:

Total Sales

Total Profit

Total Orders

# Visuals:

Sales by Product (Clustered Column Chart)

Profit by Region

Month-over-Month Sales Trend (Line Chart)

Top 10 Products by Profit (Top N Filter)

Interactive filters (Date, Region, Product)

#DAX Measures Used

DAX
Copy
Edit
Profit = SUM(Sheet1[TotalPrice]) - SUM(Sheet1[Discount]) - SUM(Sheet1[ShippingCost])

Total Sales = SUM(Sheet1[TotalPrice])

Total Orders = DISTINCTCOUNT(Sheet1[OrderID])

# How to Use

Open the .pbix file in Power BI Desktop.

Explore filters on Region, Product, and Date to see interactive changes.

Check KPI cards at the top for a quick business summary.

Modify visuals or extend it with your own calculations.

# Skills Demonstrated

Power BI dashboard design

DAX for calculated measures

Data visualization best practices

Interactive filters and drill-downs

Top N analysis using Filters pane
