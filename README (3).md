# Superstore Sales Dashboard

**By Chisom Precious**

## Overview
This project is an interactive sales performance dashboard built for a fictional retail "Superstore" business. The goal was to take raw transactional sales data and turn it into a clear, visual dashboard that highlights overall performance, top-selling categories, and trends over time, helping stakeholders quickly understand where the business is making (or losing) money.

## Tools Used
- **Microsoft Excel** – data cleaning, preparation, and pivot table analysis
- **Power BI / Power Pivot (Dashboard view in Excel)** – building the interactive visual dashboard

## Dataset
The dataset (`SALES_DATA.xlsx`) is a sales records table containing **9,995 orders** with the following fields:

- Order ID, Order Date, Ship Date, Ship Mode
- Customer ID, Customer Name, Segment
- Country, City, State, Postal Code, Region
- Product ID, Category, Sub-Category, Product Name
- Sales, Quantity, Discount, Profit
- Derived fields: Year, Month, Daily (extracted from Order Date)

The workbook contains three sheets:
1. **Sales Data** – the raw cleaned dataset
2. **Pivot** – pivot tables summarizing sales, profit, and quantity
3. **Sales Dashboard** – the final visual dashboard

## Dashboard Highlights

### Page 1: Sales Overview
- **KPI Cards**: Total Profit (286.40K), Total Quantity (38K), Total Sales (2.30M)
- **Year Filter**: Slicer to filter results by year (2020–2023)
- **Sales by City**: Top 10 cities ranked by sales (New York City leads)
- **Sales by Region**: Comparison across West, East, Central, and South
- **Sales by Segment**: Breakdown by Consumer, Corporate, and Home Office
- **Sales by Sub-Category**: Ranked bar chart from Phones (highest) to Fasteners (lowest)

### Page 2: Category & Trend Analysis
- **Qty by Category**: Technology (38.40%), Furniture (32.30%), Office Supplies (31.30%)
- **Sales Category %**: Donut chart showing the sales split between Technology, Furniture, and Office Supplies
- **Monthly Sales**: Bar chart showing sales trend across all 12 months, with November and December as peak months
- **Daily Sales**: Line chart tracking daily sales fluctuations across the month

## Key Insights
- **Technology** is the strongest category by both quantity sold and revenue share
- **Standard Class** is by far the most used shipping method (59.12%), followed by Second Class (19.99%) and First Class (15.30%)
- **Consumer** segment drives the largest share of sales, followed by Corporate and Home Office
- Sales peak toward the end of the year (Nov–Dec), suggesting strong seasonal/holiday demand
- **New York City, Los Angeles, and Seattle** are the top-performing cities by sales
- **Phones, Chairs, and Storage** are the top sub-categories driving revenue

## Project Workflow
1. Imported and cleaned raw sales data in Excel
2. Created calculated columns (Year, Month, Day) from the Order Date field
3. Built pivot tables to summarize sales, profit, and quantity across categories, regions, and time periods
4. Designed an interactive dashboard using charts (bar, donut, line) and KPI cards
5. Added slicers/filters to allow dynamic exploration by year

## Files in This Repository
- `SALES_DATA.xlsx` – Full dataset with pivot tables and dashboard
- `super.png` – Dashboard Page 1 (Sales Overview)
- `super_2.png` – Dashboard Page 2 (Category & Trend Analysis)

## Author
**Chisom Precious**
