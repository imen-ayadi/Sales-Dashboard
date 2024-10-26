# 📊 Sales Analysis Power BI Dashboard

Welcome to the **Sales Analysis Dashboard** repository. This project showcases a dynamic Power BI dashboard built to provide **in-depth insights** into sales performance across multiple dimensions such as **products, customers, regions,** and **financial metrics**. The dashboard is designed to support strategic decision-making by providing a visually appealing and interactive platform for analyzing sales data.

---

## 🚀 Project Overview

This **Sales Analysis Dashboard** is built to help business stakeholders and data enthusiasts gain actionable insights into various aspects of sales. It consolidates data from different tables and enables multi-dimensional analysis. Users can **interactively explore sales trends, identify high-performing products, understand customer demographics,** and **assess regional performance**.

The goals of this dashboard are to:
1. Provide a **clear, concise view** of overall sales performance.
2. Offer detailed insights into **customer and product-based trends**.
3. Facilitate **strategic planning** by visualizing financial metrics and regional data.

---

## 📐 Data Model

The data model is central to this dashboard, combining multiple tables to support detailed analysis. Here's an overview of each table:

- **fact_sales**: Contains transactional data such as `OrderDate`, `Profit`, `TotRevenue`, `TotOrders`, and other essential sales metrics.
- **Dim_calendar**: A comprehensive date dimension table used for time-based analysis, with fields like `Date`, `Month`, `Year`, `Weekday`, and `Quarter`.
- **Product_Categories**: Holds information on product categories, linked to subcategories for detailed product analysis.
- **Customers**: Contains demographic details about customers, such as `AnnualIncome`, `MaritalStatus`, and `EducationLevel`.
- **Returns**: Stores return information for each product, enabling return rate analysis by product.
- **Territories**: Provides geographical data, linking sales transactions to regions and countries.

Below is the data model used in Power BI:

![Data Model](path/to/data-model.png)

---

## 🖥️ Dashboard Sections & Visuals

The dashboard is organized into multiple sections, each designed to provide targeted insights. Here’s a breakdown of each page:

### 1. Home Page
   - **Purpose**: Acts as a landing page, offering quick navigation options to each analytical section: **Product, Customer, Product Details, Region,** and **Ranking**.
   - **Key Visual**: Icons for each section for intuitive navigation.
   - ![Home Page](path/to/home-page.png)

### 2. Product Analysis
   - **Content**: Analyzes sales performance by product category and subcategory.
   - **Visuals**: 
     - **Sankey Diagram**: Visualizes revenue flow by product category and subcategory.
     - **Bar Chart**: Year-over-year revenue comparison for top product categories.
   - **Insight**: Identifies top-performing products, helping in strategic product planning.
   - ![Product Analysis](path/to/product-analysis.png)

### 3. Customer Insights
   - **Content**: Examines customer demographics and purchase patterns.
   - **Visuals**:
     - **Donut Chart**: Shows customer distribution by `Marital Status` and `Parenting Status`.
     - **Bar Chart**: Sales by customer `Occupation`.
     - **Stacked Bar Chart**: Sales by product and gender.
   - **Insight**: Provides a clear view of customer profiles, assisting in targeted marketing efforts.
   - ![Customer Insights](path/to/customer-insights.png)

### 4. Geographical Analysis
   - **Content**: Visualizes sales across different countries and income levels.
   - **Visuals**:
     - **Map**: Interactive map highlighting total orders by country, segmented by income level.
     - **Flag Icons**: Country filters for an easy selection of regions.
   - **Insight**: Reveals geographical sales distribution, identifying high-potential regions for expansion.
   - ![Geographical Analysis](path/to/geographical-analysis.png)

### 5. Financial Performance
   - **Content**: Tracks quarterly financial performance and revenue targets.
   - **Visuals**:
     - **Line Chart**: Monthly revenue compared to target goals.
     - **Bar Chart**: Profit analysis by quarter.
     - **Pie Chart**: Cost breakdown by subcategory.
   - **Insight**: Helps assess progress towards financial goals and analyze profitability across categories.
   - ![Financial Performance](path/to/financial-performance.png)

### 6. Product Ranking
   - **Content**: Ranks top products by revenue and profit contribution.
   - **Visuals**:
     - **Table**: Detailed breakdown of top products with revenue and profit metrics.
     - **Bar Chart**: Visualization of top `N` products based on total revenue.
   - **Insight**: Identifies key revenue drivers and top-performing products for sales strategy.
   -
