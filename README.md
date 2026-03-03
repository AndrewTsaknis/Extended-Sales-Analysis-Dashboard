# Extended-Sales-Analysis-Dashboard
A complete Business Intelligence sales analysis project built in Excel using Power Query, Power Pivot, and DAX. The solution includes a star schema data model, time intelligence calculations (YoY growth, rolling revenue), customer behavior metrics such as Active Customers and Repeat Purchase Rate, presented in an interactive performance dashboard.
# Extended Sales Analysis Dashboard 📊

## 📌 Project Summary
This project performs an extended business intelligence analysis of a retail sales dataset using Excel, Power Query, Power Pivot, and DAX.  
The goal is to uncover insights on sales performance, customer behavior, promotions, and order fulfillment, while providing an interactive dashboard to visualize key metrics dynamically.

The analysis includes:

- Building a **star schema** data model with FactSales and dimension tables (DimDate, DimCustomer).  
- Cleaning and transforming data using **Power Query**.  
- Creating measures and KPIs with **DAX**, including Total Revenue, Total Orders, YoY Growth, Rolling 3-Month Revenue, Active Customers (90-Day), and Repeat Purchase Rate.  
- Visualizing results with PivotTables, charts, and slicers in an interactive **Dashboard** sheet.

This project demonstrates advanced Excel BI techniques and data modeling practices for portfolio or professional use.

---

## 📂 Dataset Location

Place the dataset file in the same folder as the Excel workbook:

- `OnlineRetail.xlsx` (raw dataset, ~400k+ rows)  

The project workbook (`extended-sales-analysis-dashboard.xlsx`) is designed to load and transform this file automatically via Power Query.

---

## 🔗 Dataset Download

You can download the raw dataset here:

**Online Retail Dataset (UCI Machine Learning Repository):**  
https://archive.ics.uci.edu/ml/datasets/online+retail  

---

## 📊 Key Insights & Dashboard Features

The **Dashboard** sheet includes:

1. **Revenue Metrics**
   - Total Revenue by Region or Month  
   - Year-over-Year revenue growth  
   - Rolling 3-month revenue trends  

2. **Customer Metrics**
   - Total Customers  
   - Active Customers (last 90 days)  
   - Repeat Purchase Rate  

3. **Sales Metrics**
   - Total Orders  
   - Average Order Value  

4. **Interactive PivotTables & Charts**
   - Slicers allow filtering by Month, Year, or Customer segment  
   - All measures are calculated dynamically with DAX  

---

## 🛠️ How to Use the Workbook

1. Open `extended-sales-analysis-dashboard.xlsx` in Excel 2016 or later.  
2. Enable **Data Model** if prompted.  
3. Refresh all queries to load the raw dataset into Power Pivot:  
   `Data → Refresh All`  
4. Navigate to the **Dashboard** sheet to explore KPIs,and charts.  

---

## 🌍 Notes

- The workbook uses **Power Query** to clean and transform raw data.  
- **Power Pivot** creates relationships between tables and allows advanced DAX measures.  
- The dashboard is dynamic: any updates to the raw dataset will automatically refresh metrics.  
- You can expand analysis with additional DAX measures, charts, or new dimensions as needed.

---
