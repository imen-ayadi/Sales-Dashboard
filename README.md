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

![Screenshot_110](https://github.com/user-attachments/assets/280c8a70-aaf7-4e9e-8538-b02b4f5d3d57)
![Screenshot_111](https://github.com/user-attachments/assets/25c3edf4-18dd-437b-9d41-745842246c43)

---

## 🖥️ Dashboard Sections & Visuals

The dashboard is organized into multiple sections, each designed to provide targeted insights. Here’s a breakdown of each page:

### 1. Home Page
   - **Purpose**: Acts as a landing page, offering quick navigation options to each analytical section: **Product, Customer, Product Details, Region,** and **Ranking**.
   - **Key Visual**: Icons for each section for intuitive navigation.
   - ![Screenshot_112](https://github.com/user-attachments/assets/8373e7fc-5fbe-461d-b1a9-165472725baf)


### 2. Product Analysis
   - **Content**: Analyzes sales performance by product category and subcategory.
   - **Visuals**: 
     - **Sankey Diagram**: Visualizes revenue flow by product category and subcategory.
     - **Bar Chart**: Year-over-year revenue comparison for top product categories.
   - **Insight**: Identifies top-performing products, helping in strategic product planning.
   - ![Screenshot_113](https://github.com/user-attachments/assets/267ba407-7c91-4724-a269-7f05fbee1b9c)


### 3. Customer Insights
   - **Content**: Examines customer demographics and purchase patterns.
   - **Visuals**:
     - **Donut Chart**: Shows customer distribution by `Marital Status` and `Parenting Status`.
     - **Bar Chart**: Sales by customer `Occupation`.
     - **Stacked Bar Chart**: Sales by product and gender.
   - **Insight**: Provides a clear view of customer profiles, assisting in targeted marketing efforts.
   - ![Screenshot_114](https://github.com/user-attachments/assets/b66ec163-bf82-4f94-bb0c-4d5cabcf312f)

### 4. Geographical Analysis
   - **Content**: Visualizes sales across different countries and income levels.
   - **Visuals**:
     - **Map**: Interactive map highlighting total orders by country, segmented by income level.
     - **Flag Icons**: Country filters for an easy selection of regions.
   - **Insight**: Reveals geographical sales distribution, identifying high-potential regions for expansion.
   - ![Screenshot_116](https://github.com/user-attachments/assets/586e4ac6-9cc5-43da-9f8a-2cde4fc2d8fc)


### 5. Financial Performance
   - **Content**: Tracks quarterly financial performance and revenue targets.
   - **Visuals**:
     - **Line Chart**: Monthly revenue compared to target goals.
     - **Bar Chart**: Profit analysis by quarter.
     - **Pie Chart**: Cost breakdown by subcategory.
   - **Insight**: Helps assess progress towards financial goals and analyze profitability across categories.
![Screenshot_118](https://github.com/user-attachments/assets/900ba465-354f-41f6-a073-b7719299c58a)

### 6. Product Ranking
   - **Content**: Ranks top products by revenue and profit contribution.
   - **Visuals**:
     - **Table**: Detailed breakdown of top products with revenue and profit metrics.
     - **Bar Chart**: Visualization of top `N` products based on total revenue.
   - **Insight**: Identifies key revenue drivers and top-performing products for sales strategy.
   -![Screenshot_117](https://github.com/user-attachments/assets/c6efedd5-bddd-4edf-853d-33665bb1d34c)
   ## 🛠️ How to Use the Dashboard

### Setup Instructions
1. **Prerequisites**: Ensure Power BI Desktop is installed.
2. **Download**: Clone or download the `.pbix` file from this repository.
3. **Open File**: Open the `.pbix` file in Power BI Desktop.
4. **Data Refresh**: If connected to live data sources, refresh the data to ensure visuals are up-to-date.

### Navigating the Dashboard
1. **Home Page**: Start at the Home Page to select a section for analysis.
2. **Interactive Filters**: Each page includes slicers and filters, such as `Year`, `Product Category`, and `Subcategory`, for focused analysis.
3. **Drill-Downs**: Click on visuals to explore underlying details and segment data further.
4. **Tooltips**: Hover over data points for additional metrics and insights.

---

## 🔍 Data Insights & Interpretation Guide

- **Revenue Analysis**: The Product Analysis page allows you to see which categories drive the highest revenue, helping identify profitable areas.
- **Customer Segmentation**: Use Customer Insights to determine which demographics contribute most to sales, informing targeted marketing strategies.
- **Regional Performance**: The Geographical Analysis highlights regions with high sales volumes, guiding regional sales strategies.
- **Financial Health**: The Financial Performance page offers a quick assessment of whether revenue targets are being met, with quarterly breakdowns for seasonality insights.
- **Top Product Ranking**: The Product Ranking page showcases the best performers, helping focus on products that maximize revenue.

---

## 📝 License
This project is licensed under the MIT License. Please see the [LICENSE](LICENSE) file for more information.

---

