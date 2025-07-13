# Madhav Store - Power BI Online Sales Dashboard (India)

## Problem Statement

Madhav Store is expanding rapidly across India through online retail. They needed a centralized dashboard to track key sales metrics, analyze regional performance, understand customer behavior, and identify trends across products and categories.

The goal: Turn raw data into actionable insights for smarter business decisions.

## Objectives
Monitor sales, profit, and orders across states and cities.

Analyze performance by product category and sub-category.

Track customer purchasing patterns and payment preferences.

Identify top-performing regions, peak sales months, and profitable items.

## Dataset Overview
The dashboard is built using two CSV files:


1. Details.csv

## Data used 
https://github.com/sonalisaini645/POWER-BI-dashboard/blob/main/Details.csv

Column	Description

Order ID	Unique order identifier

Amount	Sales revenue for the order

Profit	Profit earned from the order

Quantity	Number of items purchased

Category	Product category (e.g., Electronics)

Sub-Category	Specific product type (e.g., Phones)

PaymentMode	Payment method (COD, EMI, Credit Card, etc.)

2. Orders.csv
   
## Data used

https://github.com/sonalisaini645/POWER-BI-dashboard/blob/main/Orders.csv

Column	Description

Order ID	Unique order identifier

Order Date	Date of order placed

CustomerName	Name of the customer

State	State of delivery

City	City of delivery

🔗 Join Key: Order ID (to relate both tables)

## Power BI Development Process
🔹 Data Preparation
Imported both CSVs and created a one-to-many relationship using Order ID.

Transformed Order Date into Date/Month/Year format for time analysis.

Checked for null values and handled them (none found).

## Dashboard Components
Card Visuals:

Total Sales

Total Profit

Total Orders

Average Quantity

Charts:

Sales by State and City (Bar/Map)

Profit by Category/Sub-Category

Sales Trend over Time (Line)

Top Cities by Revenue

Quantity vs Profit (Scatter)

Slicers for dynamic filtering:

Order Date

Category / Sub-Category

Payment Mode

State / City

##  Sample Insights
 Total Orders: 500

 Top Earning State: Maharashtra

 Top City by Sales: Mumbai

 Most Ordered Category: Electronics

 Popular Payment Method: Credit Card

## Sales Peak: October–December (based on Order Date)

## Deployment
Dashboard published to Power BI Service

Shared with Madhav Store management

Daily auto-refresh scheduled for updated data
## Dashboard Image
https://github.com/sonalisaini645/POWER-BI-dashboard/blob/main/screenshot%20dashboard.png

## Description
I have created a project in excel, creating multiple dashboards and tables to analyze the data .This process involved several stages imcluding data processing ,data cleaning and data visualization.
