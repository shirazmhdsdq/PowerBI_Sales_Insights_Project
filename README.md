# Sales Insights & Trend Analysis Dashboard

## 📌 Project Overview
This project is an end-to-end business intelligence dashboard built in Power BI. It is designed to visualize revenue KPIs, regional performance, and long-term sales trends. The project demonstrates a complete data pipeline from multi-source extraction to relational data modeling and advanced DAX calculations.

## 🛠️ Tech Stack & Tools
* **Power BI Desktop:** Dashboard design, interactive data visualization, and reporting.
* **Power Query:** Multi-source ETL (Extract, Transform, Load) processes to clean data types, handle locale-specific number formatting, and ensure consistency across tables.
* **DAX (Data Analysis Expressions):** Programmed custom measures (e.g., Total Revenue) for dynamic KPI tracking.
* **Data Modeling:** Built a robust Star Schema architecture utilizing 1-to-many relationships between Fact and Dimension tables.

## 📂 Project Structure
* `Sales_Insights_Dashboard.pbix`: The master Power BI project file containing the Star Schema model, DAX measures, and final report.
* `Raw_Data/`: The original multi-table CSV dataset containing Fact_Sales, Dim_Products, and Dim_Customers/Regions.
* `![Dashboard Screenshot](Screenshot%202026-10-04%20143845.png)`: A high-resolution static preview of the interactive dashboard.

## 📈 Key Features & Insights
* **Star Schema Architecture:** Successfully mapped product and territory dimensions to a centralized sales fact table using unique identifier keys (`ProductKey`, `SalesTerritoryKey`).
* **Time Intelligence:** Implemented native date hierarchies to convert daily transactional data into a smooth, high-level Month-over-Month/Year-over-Year trend analysis.
* **Geospatial & Category Tracking:** Segmented grand total revenue across global territories via interactive clustered bar charts for quick executive decision-making.
