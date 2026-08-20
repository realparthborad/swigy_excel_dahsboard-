# 🍔 Swiggy Order Data Analysis — Excel Dashboard

An end-to-end Excel analysis of nearly 2 lakh (197,430) Swiggy food orders, transforming raw order-level data into an interactive dashboard using PivotTables and PivotCharts. This project explores sales trends, food preferences, quarterly performance, categories, and geography to understand how India orders food online.

## 📌 Project Overview

Food delivery platforms generate massive volumes of transactional data every day, but the real value lies in turning that data into actionable insights.

This project takes a raw Swiggy order dataset containing state, city, restaurant, dish, price, rating, date, and other attributes and transforms it into a structured Excel dashboard.

The analysis answers questions such as:

* How much revenue did Swiggy generate?
* What is the Average Order Value (AOV)?
* Is India's online food demand more Veg or Non-Veg?
* Which months, days, and quarters generate the highest sales?
* Which states and cities contribute the most revenue?
* How are different food categories performing?

## 🗂️ Dataset

| Detail         | Value                            |
| -------------- | -------------------------------- |
| Records        | 197,430 orders                   |
| Columns        | 14                               |
| Time Period    | January 2025 – August 2025       |
| States Covered | 27 Indian states                 |
| Currency       | INR                              |
| Data Type      | Food delivery order transactions |

### Dataset Columns

* State
* City
* Order Date
* Day
* Quarter
* Week
* Restaurant Name
* Location
* Category
* Dish Name
* Food Type
* Price (INR)
* Rating
* Rating Count

The raw dataset is available in the **Swiggy Data** sheet and acts as the source of truth for the analysis.

## 🧮 Workbook Structure

### 1. Swiggy Data

Contains the raw and cleaned order-level dataset used as the primary data source.

### 2. ANALYSIS

Contains the PivotTables and supporting analysis used to generate:

* KPI metrics
* Monthly sales trends
* Daily sales trends
* Quarterly performance
* Veg vs Non-Veg analysis
* State-level sales
* Top 5 cities by sales
* Food category performance

### 3. DASHBOARD

A consolidated interactive dashboard containing KPI cards, PivotCharts, and visual summaries for quick business reporting.

## 🔑 Key Insights

* **Total Sales:** ₹5.30 Cr
* **Total Orders:** 197,430
* **Average Order Value (AOV):** ₹268.5
* **Average Customer Rating:** 4.34/5
* **Cumulative Rating Count:** 55.9 lakh+
* **Veg Orders:** ~72%
* **Non-Veg Orders:** ~28%

### Quarterly Performance

* **Q2:** ₹1.99 Cr — approximately 37.5% of total sales
* **Q1:** ₹1.97 Cr — approximately 37.1% of total sales
* **Q3:** approximately 25.4% of total sales

Q2 was the strongest quarter, closely followed by Q1.

### Day-Wise Performance

**Saturday** generated the highest sales at approximately **₹77.8L**, followed by Thursday and Friday. This indicates stronger food-ordering activity toward the end of the week and weekend.

### Food Preferences

Veg food dominates the order mix, accounting for approximately **72% of orders**, compared with around **28% for Non-Veg**.

### Category Performance

**Recommended** was the most-ordered category, with approximately **24,100 orders**, indicating that customers frequently rely on platform recommendations when selecting food.

### Geographic Performance

* **Karnataka** was the highest-revenue state with approximately **₹54.6L** in sales.
* **Bengaluru** was the leading city by revenue.
* Other leading cities included **Lucknow, Hyderabad, Mumbai, and New Delhi**.

## 🛠️ Tools & Techniques Used

* Microsoft Excel
* PivotTables
* PivotCharts
* KPI Cards
* Data Cleaning & Preprocessing
* Date Parsing
* Category Standardization
* Null Value Handling
* Time-Series Analysis
* Monthly, Daily & Quarterly Trend Analysis
* State & City-Level Analysis
* Food Category Segmentation
* Dashboard Design
* Business Insight Generation

## 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data cleaning and preprocessing at scale (~200K rows)
* Exploratory Data Analysis (EDA) using Excel
* KPI definition and dashboard development
* Time-series analysis
* Geographic sales analysis
* Customer preference analysis
* Category-level performance analysis
* PivotTable and PivotChart development
* Business storytelling and insight generation
* Executive dashboard design

## 📊 Dashboard Features

The interactive dashboard provides a high-level view of business performance through:

* Total Sales KPI
* Average Order Value KPI
* Average Rating KPI
* Total Order Count KPI
* Monthly Sales Trend
* Day-Wise Sales Trend
* Quarterly Sales Analysis
* Veg vs Non-Veg Order Split
* State-Wise Sales Analysis
* Top 5 Cities by Revenue
* Category-Level Order Analysis

The workbook is built using PivotTables and PivotCharts, allowing the analysis to be refreshed when the underlying source data changes.

## 📁 Project File

**Swiggy_Raw_Data_Excel.xlsx**

The workbook contains:

* Raw/cleaned order data
* PivotTables
* PivotCharts
* Analysis sheets
* Interactive dashboard

## 🚀 How to Use

1. Open `Swiggy_Raw_Data_Excel.xlsx` in Microsoft Excel.
2. Start with the **DASHBOARD** sheet for the executive overview.
3. Navigate to **ANALYSIS** to explore the individual PivotTables and charts.
4. Check **Swiggy Data** to view the complete order-level dataset.
5. If new data is added, use **Data → Refresh All** in Excel to refresh the PivotTables and dashboard.

## 🙋 About the Project

This project was created as a hands-on Excel data analysis exercise to demonstrate how large-scale raw food-delivery transaction data can be transformed into meaningful business insights.

The project focuses on practical data analytics without programming, using structured data cleaning, PivotTables, PivotCharts, KPI development, and dashboard design.

The goal is to turn nearly 2 lakh raw food orders into a clear, interactive, and business-focused analytical dashboard.

---

⭐ **If you find this project useful, feel free to explore the workbook, fork the idea, and share your feedback.**
