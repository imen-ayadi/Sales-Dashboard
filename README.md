# 📊 Sales Analysis Power BI Dashboard

Welcome to the **Sales Analysis Dashboard** repository. This project showcases a dynamic Power BI dashboard built to provide **in-depth insights** into sales performance across multiple dimensions such as **products, customers, regions,** and **financial metrics**. The dashboard is designed to support strategic decision-making by providing a visually appealing and interactive platform for analyzing sales data.

## 🚀 Project Overview

This **Sales Analysis Dashboard** is built to help business stakeholders and data enthusiasts gain actionable insights into various aspects of sales. It consolidates data from different tables and enables multi-dimensional analysis. Users can **interactively explore sales trends, identify high-performing products, understand customer demographics,** and **assess regional performance**.

The goal of this dashboard is to:
1. Provide a **clear, concise view** of overall sales performance.
2. Offer detailed insights into **customer and product-based trends**.
3. Facilitate **strategic planning** by visualizing financial metrics and regional data.

## 📐 Data Model

The data model is central to this dashboard, combining multiple tables to support detailed analysis. Here's an overview of each table:

- **fact_sales**: Contains transactional data such as `OrderDate`, `Profit`, `TotRevenue`, `TotOrders`, and other essential sales metrics.
- **Dim_calendar**: A comprehensive date dimension table used for time-based analysis, with fields like `Date`, `Month`, `Year`, `Weekday`, and `Quarter`.
- **Product_Categories**: Holds information on product categories, linked to subcategories for detailed product analysis.
- **Customers**: Contains demographic details about customers, such as `AnnualIncome`, `MaritalStatus`, and `EducationLevel`.
- **Returns**: Stores return information for each product, enabling return rate analysis by product.
- **Territories**: Provides geographical data, linking sales transactions to regions and countries.

## 🖥️ Dashboard Sections & Visuals

### 1. Home Page
   - **Purpose**: Acts as a landing page, offering quick navigation options to each analytical section: **Product, Customer, Product Details, Region,** and **Ranking**.
   - ![Home Page](path/to/home-page.png)
