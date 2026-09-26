# E-Commerce Sales, Customer & Product Analytics

## Project Overview

This project analyzes e-commerce sales, customer, product, regional, and profitability data using Excel, MySQL, and Power BI.

## Business Problem

E-commerce businesses generate large amounts of transactional data, but raw data alone does not provide clear business insights.

This project focuses on analyzing sales, customer, product, regional, and profitability data to answer important business questions such as:

- How are sales changing over time?
- Which categories and products generate the most sales?
- Which categories and products are most profitable?
- Which customers contribute the most revenue?
- Which regions perform better?
- How frequently do customers purchase?
- What is the Average Order Value (AOV)?

## Project Objectives

- Analyze overall sales and profit performance
- Identify monthly sales trends
- Compare category and sub-category performance
- Analyze regional performance
- Identify top customers and products
- Analyze repeat customer behavior
- Calculate Average Order Value (AOV)
- Analyze product rankings within categories
- Calculate monthly revenue growth
- Calculate cumulative revenue
- Build an interactive Power BI dashboard

## Tools & Technologies

- Microsoft Excel – Data exploration, cleaning, validation and initial analysis
- MySQL – SQL-based business analysis
- Power BI – Interactive dashboard and data visualization
- DAX – Power BI measures and calculations
- GitHub – Project documentation and portfolio management

## Dataset

The dataset contains e-commerce transactional data covering:

- Order details
- Customer information
- Product information
- Sales
- Quantity
- Discount
- Profit
- Shipping information
- Geographic information
- Return information

The dataset contains approximately 10,194 order-line records.

## Project Workflow

The project follows an end-to-end data analytics workflow:

```text
Raw Data
   ↓
Excel Data Exploration
   ↓
Data Cleaning & Validation
   ↓
MySQL Data Analysis
   ↓
Business Questions & SQL Queries
   ↓
Power BI Data Modeling
   ↓
DAX Measures
   ↓
Interactive Dashboard
   ↓
Business Insights

## SQL Analysis

The SQL analysis was performed using MySQL to answer business questions across sales, customers, products, profitability, and time-based performance.

### Sales Analysis

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Average Order Value (AOV)
- Monthly Sales
- Highest and Lowest Sales Month
- Category Performance
- Sub-Category Performance
- Regional Performance

### Customer Analysis

- Top Customers by Sales
- Repeat Customers
- Customer Purchase Frequency
- Regional Average Order Value
- Customer Previous Order Analysis

### Product Analysis

- Top Products by Sales
- Most Profitable Products
- Most Profitable Categories
- Product Ranking Within Category
- Top 3 Products Per Category

### Time-Based Analysis

- Monthly Revenue
- Monthly Revenue Growth
- Cumulative Revenue
- Previous Month Revenue Comparison

### SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- DISTINCT
- CTEs (Common Table Expressions)
- Window Functions
- RANK()
- LAG()
- Date Functions
- Conditional Filtering

## Power BI Dashboard

![Power BI Dashboard](screenshots/dashboard.png)

The Power BI dashboard provides an interactive overview of e-commerce business performance.

### Key Performance Indicators

- Total Sales
- Total Profit
- Total Orders
- Average Order Value (AOV)

### Dashboard Visualizations

- Monthly Sales Trend
- Sales by Category
- Top 10 Products by Sales
- Sales by Segment
- Profit by Category
- Top Performers

### Interactive Filters

The dashboard includes slicers for:

- Region
- Category
- Order Date

The visuals update dynamically based on the selected filters, allowing users to explore different segments of the business.

### DAX Measures

The dashboard uses DAX measures for KPI calculations and analytical metrics, including:

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Orders = DISTINCTCOUNT(Orders[Order ID])

Total Quantity = SUM(Orders[Quantity])

AOV = DIVIDE([Total Sales], [Total Orders])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

## Key Business Insights

The analysis helps identify important business patterns across sales, customers, products, regions, and profitability.

Key areas identified through the analysis include:

- Sales trends across different months
- Categories contributing significantly to overall sales
- Products generating high sales and profit
- Regional differences in sales performance
- High-value customers based on revenue contribution
- Repeat customer purchasing behavior
- Differences between sales performance and profitability
- Monthly revenue growth and cumulative revenue trends

These insights are presented through the SQL analysis and interactive Power BI dashboard.

## Project Structure

```text
E-Commerce-Sales-Customer-Analytics/
│
├── README.md
│
├── data/
│
├── excel/
│   └── Ecommerce_Sales_Analysis_Working.xlsx
│
├── sql/
│   └── ecommerce_analysis.sql
│
└── powerbi/
    └── E-Commerce-Sales-Customer-Analytics.pbix

## Skills Demonstrated

- Data Cleaning & Validation
- Exploratory Data Analysis
- Microsoft Excel
- Pivot Tables
- Data Visualization
- SQL
- MySQL
- CTEs
- Window Functions
- DAX
- Power BI
- Data Modeling
- KPI Development
- Business Analysis
- Dashboard Design
- GitHub Documentation


## Author

**RISHITHA CHOKKAPU**

B.Tech – Electronics & Communication Engineering  
2026 Graduate
