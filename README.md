📝 Overview

This project is an interactive Power BI dashboard built to analyze Apple’s retail sales data.
It provides insights into products, categories, stores, sales, and warranty claims, enabling both executives and analysts to explore performance trends and make data-driven decisions.

📂 Data Sources

The dashboard integrates multiple CSV datasets:

sales.csv → Transaction-level sales records

products.csv → Product details with pricing and launch info

category.csv → Product categories

stores.csv → Store details (city, country, store_id)

warranty.csv → Warranty claims linked to sales

🏗️ Data Modeling

Created a star schema model with fact (Sales) and dimension tables (Products, Category, Stores, Date, Warranty).

Built a custom Date table to support time intelligence (YTD, YoY, Month, Quarter).

Converted IDs to Whole Numbers and cleaned text fields for consistency.

📈 Key Measures (DAX)

Total Revenue = SUMX(Sales × Product Price)

Total Quantity Sold

Average Selling Price (ASP)

Revenue YoY % Growth

Revenue YTD

Warranty Claim Rate (per 1,000 units)

Average Days to Claim

🎨 Dashboard Pages

Overview → KPIs, revenue trends, category breakdown, country sales map

Products → Category & product performance, top sellers, decomposition tree

Stores → Store-level analysis, geography insights, revenue per store

Warranty → Claims tracking, claim rate, repair status, avg days to claim

Tooltips & Drillthrough → Product and store drill-downs for deeper insights

⚡ Advanced Features

Dynamic Field Parameters → Switch between metrics, dimensions, and time grains

Drillthrough & Tooltips → Context-specific detail pages

Row-Level Security (RLS) → User-specific access by country

Bookmarks & Buttons → Page navigation and executive vs. analyst views

Custom Apple-inspired Theme → Minimal, clean design with compact view option

🚀 Outcomes

Gave executives a clear overview of sales KPIs.

Empowered analysts with detailed product, store, and warranty analysis.

Improved decision-making by highlighting trends, growth, and risk areas.
