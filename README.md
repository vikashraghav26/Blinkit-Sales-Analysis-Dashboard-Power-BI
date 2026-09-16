# 🛵 Blinkit Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard analyzing sales performance for **Blinkit**, India's quick-commerce ("last minute") grocery delivery platform — covering item-level sales, fat content, outlet characteristics, and establishment trends to support inventory, merchandising, and outlet-strategy decisions.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-brightgreen?style=for-the-badge)

---

## 📌 Project Description

This project turns Blinkit's outlet and item sales data into a single-page Power BI dashboard built for category managers, supply-chain planners, and business analysts. The report surfaces total sales, average sales, item count, and customer ratings, then breaks performance down by item type, fat content, outlet size, outlet location tier, and outlet establishment year — helping identify which products and outlet formats drive the most revenue.

The report answers key business questions such as:
- What are total sales, average sales per transaction, total item count, and average customer rating?
- How has outlet establishment (and resulting sales) trended by year?
- Which item types and fat-content categories generate the most sales?
- How does "Low Fat" vs. "Regular" sales performance vary by outlet location tier (Tier 1/2/3)?
- How does outlet size (Small, Medium, High) affect sales distribution?
- Which outlet types (Supermarket Type1/2/3, Grocery Store) perform best across sales, ratings, and item visibility?

---

## ✨ Features

- **📋 KPI Summary Cards** — Total Sales, Avg. Sales, No. of Items, Avg. Rating
- **📈 Outlet Establishment by Year** — Line chart tracking outlet growth/sales trend from 2012–2022 with peak-year callouts
- **🔄 Interactive Measure Tabs** — Toggle between Total Sales, Avg Sales, No. of Items, and Avg Rating to dynamically re-drive the Fat Content and Item Type visuals
- **🍩 Fat Content Breakdown** — Donut chart comparing Low Fat vs. Regular product sales
- **📊 Fat Content by Outlet Location Tier** — Grouped bar chart comparing Low Fat vs. Regular sales across Tier 1, Tier 2, and Tier 3 locations
- **🥦 Item Type Ranking** — Horizontal bar chart ranking all product categories (Fruits & Vegetables, Snack Foods, Household, Frozen Foods, Dairy, etc.) by the selected measure
- **🍩 Outlet Size Breakdown** — Donut chart segmenting sales by Medium, Small, and High outlet size
- **📶 Outlet Location Type** — Stacked bar showing sales share across Tier 1, Tier 2, and Tier 3 locations
- **📋 Outlet Type Performance Table** — Sortable table comparing Total Sales, Avg Sales, No. of Items, Avg Rating, and Item Visibility across Supermarket Type1/2/3 and Grocery Store
- **🎛️ Dynamic Filtering** — Slicers for Outlet Location Type, Outlet Size, and Item Type
- **🎨 Custom Theme** — Blinkit-branded yellow sidebar with a clean white canvas and green/gold accent palette

---

## 🛠️ Technologies Used

| Tool / Skill | Purpose |
|---|---|
| **Power BI Desktop** | Report design, data modeling, and visualization |
| **Power Query (M)** | Data cleaning, shaping, and transformation |
| **DAX (Data Analysis Expressions)** | Calculated measures (Avg. Sales, Avg. Rating, dynamic measure switching via field parameters/SWITCH) |
| **Data Modeling** | Relationship modeling between item, outlet, and sales tables |
| **Excel / CSV** | Source data format (Blinkit outlet and item sales export) |

---

## 📈 Key Metrics Tracked

| KPI | Description |
|---|---|
| **Total Sales** | Sum of all item sales across outlets |
| **Avg Sales** | Average sales value per item/transaction |
| **No. of Items** | Total distinct items sold |
| **Avg Rating** | Average customer rating across items/outlets |
| **Item Visibility** | Average visibility/shelf-presence score per outlet type |
| **Sales by Fat Content** | Low Fat vs. Regular sales split |
| **Sales by Outlet Tier** | Distribution of sales across Tier 1, Tier 2, and Tier 3 outlet locations |

---

## 🗂️ Project Structure

```
blinkit-sales-analysis-dashboard/
│
├── screenshots/
│   └── 1_dashboard_overview.png
│
├── data/
│   └── blinkit_sales_data.csv          # (add your source dataset here)
│
├── Blinkit_Sales_Analysis_Dashboard.pbix   # Power BI report file
├── README.md                           # Project documentation
└── LICENSE
```

## 👤 Author

** Vikas Kumar **
📧 Email: vikashkumarsilco@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/vikash-kumar-data-analyst/
💼 Portfolio: https://vikashraghav.netlify.app/
🐙 GitHub: https://github.com/vikashraghav26



