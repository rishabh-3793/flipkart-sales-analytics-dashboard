# 🛒 FlipMart Sales Dashboard

An interactive Power BI dashboard analyzing FlipMart's sales, profit, and quantity performance across shipping modes, customer segments, product categories, and time.

## 📸 Preview

The dashboard includes two primary views:
- An **overview page** with high-level KPIs, sales by shipping mode, sales trend by year/segment, category breakdown, and profit distribution.
- A **detailed page** with monthly trends, shipping mode filters, and top-performing sub-categories.

## 📊 Key Metrics (KPI Cards)

| Metric | Value |
|---|---|
| Total Sales | 12.64M |
| Total Quantity | 178K |
| Total Transactions | 75.59M |
| Total Profit | 208.13K |

*(Values shown reflect the full dataset and update dynamically based on filters applied.)*

## 🧩 Dashboard Features

### Filters & Slicers
- **Order/Ship Date range** — interactive date slider and start/end date pickers
- **Shipping Mode** — filter by Standard Class, Second Class, First Class, or Same Day

### Visuals
- **Sum of Sales by Shipping Mode** — bar chart comparing performance across Standard Class, Second Class, First Class, and Same Day
- **Sum of Sales by Year/Month and Segment** — trend line comparing Consumer, Corporate, and Home Office segments over time
- **Sales by Category** — table of sub-category sales (Paper, Phones, Storage, Supplies, Tables, etc.) with totals
- **Top 5 Sales — Sub-Category wise** — ranked table highlighting top-performing sub-categories
- **Sum of Profit by Category** — donut chart breaking down profit share across Furniture, Office Supplies, and Technology

## 📁 Dataset

The dashboard is built on FlipMart's sales transaction data, including fields such as:
- Order/Ship Date
- Sales, Quantity, Profit, Transaction count
- Shipping Mode
- Customer Segment (Consumer, Corporate, Home Office)
- Category / Sub-Category

*(Add the actual dataset name/source and file path here, e.g. `data/flipmart_sales.csv`.)*

## 🛠️ Tools Used

- **Power BI Desktop** for data modeling, DAX measures, and dashboard design

## 🗂️ Repository Structure

```
├── data/                            # Raw/cleaned sales dataset
├── FlipMart_Sales_Dashboard.pbix    # Power BI dashboard file
├── screenshots/                     # Dashboard preview images
└── README.md
