🍔 Swiggy Order Data Analysis — Excel Dashboard

An end-to-end Excel analysis of nearly 2 lakh (197,430) Swiggy food orders, transforming raw order-level data into a live, interactive dashboard using PivotTables and PivotCharts. This project digs into sales trends, food preferences, quarterly performance, and geography to understand how India orders food online.

📌 Project Overview

Food delivery platforms generate massive volumes of transactional data every day — but the real value lies in turning that into insight. This project takes a raw Swiggy order dataset (state, city, restaurant, dish, price, rating, date, etc.) and builds a fully interactive Excel workbook answering questions like:

How much revenue did Swiggy generate, and what's the average order value?
Is India's online food demand more Veg or Non-Veg?
Which months, days, and quarters see the highest sales?
Which states and cities drive the most revenue?
How are dish categories (Main Course, Desserts, Snacks, etc.) performing?
🗂️ Dataset
Detail	Value
Records	197,430 orders
Columns	14 (State, City, Order Date, Day, Quarter, Week, Restaurant Name, Location, Category, Dish Name, Food Type, Price (INR), Rating, Rating Count)
Time Period	Jan 2025 – Aug 2025
Coverage	27 Indian states, multiple cities
Currency	INR

The raw data lives in the Swiggy Data sheet. All analysis is built on top of it using PivotTables, so the entire workbook refreshes with one click if the source data changes.

🧮 What's Inside the Workbook
Sheet	Purpose
Swiggy Data	Raw/cleaned order-level dataset (source of truth)
ANALYSIS	PivotTables powering every KPI and chart — KPIs, monthly/day/quarter trends, food type split, state & top-5-city sales
DASHBOARD	Consolidated visual dashboard combining all charts and KPI cards in one view

Each analysis block pairs a PivotTable with a corresponding PivotChart, and the DASHBOARD sheet ties them together for at-a-glance business reporting.

🔑 Key Insights
Total sales of ₹5.30 Cr across 197,430 orders, with an Average Order Value (AOV) of ₹268.5.
Average customer rating stands strong at 4.34/5, backed by 55.9 lakh+ cumulative rating counts — a healthy trust signal.
Veg dominates demand, making up ~72% of orders vs. ~28% for Non-Veg — a clear preference in the platform's order mix.
Q2 (Apr–Jun) was the strongest quarter (₹1.99 Cr, ~37.5% of sales), closely followed by Q1 (₹1.97 Cr, ~37.1%); Q3 tapered off to ~25.4%.
Saturday is the biggest order day (₹77.8L), followed closely by Thursday and Friday — clear weekend/late-week ordering behavior.
"Recommended" is the most-ordered category by a wide margin (24,100 orders), showing customers lean heavily on platform recommendations.
Karnataka leads all states in sales (₹54.6L), and Bengaluru is the top revenue city, ahead of Lucknow, Hyderabad, Mumbai, and New Delhi in the top-5 city ranking.
🛠️ Tools & Techniques Used
Microsoft Excel
PivotTables & PivotCharts
KPI card design (Total Sales, AOV, Avg Rating, Order Count)
Data Cleaning (date parsing, category standardization, null handling)
Trend analysis (monthly / daily / quarterly)
Geographic sales breakdown (state & city level)
Dashboard consolidation for executive reporting
🎯 Skills Demonstrated
Data cleaning & preprocessing at scale (~200K rows)
Exploratory Data Analysis (EDA) in Excel
KPI definition and dashboard design
Time-series trend analysis (month/day/quarter)
Geographic and categorical segmentation
Business insight generation from raw transactional data
📁 File
Swiggy_Raw_Data_Excel.xlsx — the complete, interactive workbook (raw data + pivots + charts + dashboard)
🚀 How to Use
Open Swiggy_Raw_Data_Excel.xlsx in Excel.
Start on the DASHBOARD sheet for a quick executive overview.
Dive into ANALYSIS to explore individual PivotTables (monthly trend, food type, day trend, quarter, state, top-5 cities).
Check Swiggy Data for the full raw dataset.
Refresh all PivotTables (Data → Refresh All) if new data is added.
🙋 About

This project was built as a hands-on Excel data analysis exercise to demonstrate how large-scale raw food-delivery data can be transformed into clear, actionable business insights — no code required, just structured thinking and the right Excel tools.

Feel free to explore, fork the idea, or reach out with feedback!
