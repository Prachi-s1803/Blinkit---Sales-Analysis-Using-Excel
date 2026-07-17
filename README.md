# BlinkIT Grocery Sales Analysis

## 📌 Project Overview
This project analyzes grocery sales data for BlinkIT across multiple outlets to uncover key business insights around sales performance, customer preferences, and outlet characteristics. The workbook combines raw transactional data, pivot-table-based KPI summaries, and an interactive dashboard for stakeholder reporting.

## 🎯 Objective
To identify sales trends by product category, outlet type, location tier, and item attributes — helping business teams understand what drives sales performance and where opportunities for growth exist.

## 📂 Dataset
- **Source Sheet:** `BlinkIT Grocery Data`
- **Size:** 8,523 records × 13 columns
- **Key Fields:**
  - `Item Identifier`, `Item Type`, `Item Fat Content`, `Item Weight`, `Item Visibility`
  - `Outlet Identifier`, `Outlet Establishment Year`, `Outlet Size`, `Outlet Location Type`, `Outlet Type`
  - `Sales`, `Rating`

## 🧹 Data Cleaning
- Standardized inconsistent category labels in `Item Fat Content` (e.g., "low fat" vs "Low Fat" vs "Regular" vs"regular")
- Handled missing values in `Item Weight` (~1,463 blanks)
- Verified data types across numeric and categorical fields

## 📊 Key KPIs Calculated
| Metric | Value |
|---|---|
| Total Sales | ₹2,48,991.59 |
| Average Sales per Item | ₹142.04 |
| Number of Unique Items | 1,753 |
| Average Customer Rating | 3.95 |

## 🔍 Analysis Performed
1. **Sales by Fat Content** — Regular vs Low Fat product performance
2. **Fat Content by Outlet Location Tier** — Sales split across Tier 1/2/3 cities
3. **Sales by Item Type** — Top and bottom performing categories (Snack Foods and Fruits & Vegetables lead; Seafood and Hard Drinks lag)
4. **Sales by Outlet Establishment Year** — Performance trend of outlets opened between 2011–2022
5. **Sales by Outlet Size** — Comparison across High, Medium, and Small format stores
6. **Sales by Outlet Type** — Grocery Store vs Supermarket Type1/2/3
7. **Sales, Average Sales & Item Count by Outlet Type** — combined performance view

## 📈 Dashboard
An interactive dashboard (`Dashboard` sheet) was built using PivotTables and PivotCharts to visualize:
- Total sales and average sales trends
- Outlet-wise and category-wise performance comparisons
- Fat content and location-based breakdowns

## 🛠️ Tools Used
- **Microsoft Excel** — Data cleaning, PivotTables, PivotCharts, KPI dashboard
- Core functions/features: PivotTables, SUMIFS, conditional formatting, data validation

## 💡 Key Insights
- Regular and Low Fat items contribute nearly equal shares of total sales
- Tier 3 locations generate the highest overall sales
- Supermarket Type 1 outlets outperform other formats in both total and average sales
- Snack Foods, Fruits & Vegetables, and Frozen Foods are the top revenue-driving categories

## 🚀 How to Use
1. Open `BlinkIT_Grocery_Data_Excel.xlsx`
2. Navigate to the `Dashboard` sheet for the visual summary
3. Refer to `SheetsDesign` for the underlying pivot table calculations
4. Raw data is available in the `BlinkIT Grocery Data` sheet for further analysis

## 👤 Author
[Prachi Saini]
