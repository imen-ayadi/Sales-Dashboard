Sales Analysis Dashboard
Overview
This repository contains an interactive Power BI dashboard for analyzing sales performance across various dimensions, including products, customers, regions, and financial metrics. This dashboard is ideal for stakeholders and decision-makers looking for an in-depth analysis of sales data to identify trends, optimize product performance, and make data-driven decisions.

Features
Multi-dimensional Analysis: Explore sales data by product category, customer demographics, geographic distribution, and time.
Top Products and Revenue Insights: Visualize revenue contribution by top-performing products.
Geographical Sales Breakdown: Interactive map highlighting sales across different regions.
Customer Demographics: Analyze customer distribution by income level, gender, and marital status.
Financial Performance Indicators: Track profit, revenue, and target achievement across quarters and years.
Intuitive Visuals: Dynamic visuals including bar charts, line graphs, pie charts, and maps for comprehensive insights.
Data Model
The data model integrates several tables, including:

fact_sales: Stores transactional data such as OrderDate, Profit, TotRevenue, and TotOrders.
Dim_calendar: Provides time-based analysis with fields like Date, Month, and Year.
Product_Categories: Contains information about product categories and their respective subcategories.
Customers: Holds customer demographic data, such as CustomerKey, AnnualIncome, MaritalStatus, and EducationLevel.
Returns: Details the return quantity by product, allowing analysis of product return rates.
Dashboard Pages
Home Page

Purpose: An overview of the dashboard with quick navigation icons for each section, including Product, Customer, Product Details, Region, and Ranking.
Product Analysis

Visuals: Profit by product subcategories, revenue trend over the years, and a breakdown of revenue by individual products.
Insight: Identify the top-grossing products and track revenue contributions across years.
Customer Insights

Visuals: Customer distribution by income level and marital status, as well as total orders by gender.
Insight: Understand customer demographics and analyze their impact on sales.
Geographical Analysis

Visuals: A global map showing sales orders by country, segmented by income level.
Insight: Discover regional sales trends and identify high-performing locations.
Financial Performance

Visuals: Quarterly profit breakdown, revenue and target achievement, and cost analysis by subcategory.
Insight: Track financial KPIs to ensure sales targets are met and analyze profitability by quarter.
Product Ranking

Visuals: Revenue and profit breakdown for the top products.
Insight: Recognize the best-performing products to focus on for sales optimization.
Usage
Navigation: Use the navigation bar to access each section of the dashboard.
Filters: Dynamic slicers for Year, CategoryName, and SubcategoryName allow users to refine the displayed data.
Interactive Elements: Hover over data points for additional insights and click on items for drill-through analysis.
Screenshots
Include screenshots from each page (already provided) to help users understand the layout and purpose of each section.
How to Use
Power BI Installation: Make sure you have Power BI Desktop installed.
Load Data: Open the .pbix file in Power BI to explore the dashboard.
Customization: Adjust filters and slicers as needed to analyze specific dimensions of interest.
Data Sources
The dashboard leverages data from various sales and customer databases. Tables are linked via common keys such as ProductKey and CustomerKey to create a unified model for robust analysis.
License
This project is licensed under the MIT License - see the LICENSE file for details.
