# 📊 Sales Performance & KPI Dashboard

## 🔍 Overview

This project focuses on analyzing sales data to uncover meaningful business insights through an interactive Power BI dashboard. The goal was to transform raw transactional data into a structured and visually intuitive format that supports better decision-making.

The dashboard highlights key performance indicators such as revenue, profit, customer count, and margin, while also enabling deeper exploration across product categories, regions, and time.

---

## 🎯 Objective

The primary objective of this project was to:

* Build a centralized view of sales performance
* Track key business metrics over time
* Identify trends across regions and product categories
* Improve data quality through transformation and cleaning

---

## 🛠️ Tools & Technologies

* **Power BI** – for building interactive visualizations
* **SQL** – for data extraction, transformation, and preparation
* **DAX** – for creating calculated measures and KPIs

---

## 📈 Dashboard Highlights

* KPI cards showing Revenue, Profit, Customers, Margin, and Quantity
* Category-wise performance breakdown
* Weekly sales trends across different regions
* Dynamic filtering based on year and selected metrics
* Clean and structured data model supporting analysis

---

## 🧠 Data Preparation Approach

The dataset was prepared using SQL by combining multiple yearly tables into a single dataset.

Key steps included:

* Merging datasets using `UNION ALL`
* Creating a weekly date field for trend analysis
* Handling missing revenue values by deriving them from price and quantity
* Calculating profit using revenue and cost data
* Joining customer and product tables for enriched insights

---

## 📂 Project Structure

```
├── Sales_Dashboard.pbix       # Power BI dashboard file
├── Data_Transformation.sql    # SQL script used for data preparation
└── README.md                 # Project documentation
```

---

## 📊 Key Insights

* Certain product categories contribute significantly more to overall revenue
* Regional sales patterns vary across different time periods
* Profit margins fluctuate depending on cost structure and product mix
* Weekly trends reveal peaks that can support better planning

---

## 🚀 Future Scope

* Adding forecasting models for sales prediction
* Introducing customer segmentation analysis
* Publishing the dashboard to Power BI Service for sharing

---

## 👤 Author

**Venkatesh Metan**

---

## 💡 Note

This project is part of my data analytics portfolio and reflects my approach to solving real-world business problems using data.
