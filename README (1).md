# 📊 Sales & Revenue Analysis Dashboard

> **Thiranex Internship Task** — Interactive dashboard to analyze sales and revenue data

🔗 **Live Demo:** `https://<your-username>.github.io/sales-dashboard`

---

## Features

- **📥 Data Import** — Upload CSV files (drag & drop supported); auto-detects date, product, region, amount columns
- **📈 KPI Cards** — Total Revenue, Orders, Avg Order Value, Gross Margin, New Customers, Churn Rate
- **📊 Charts:**
  - Monthly Revenue Trend (dual-axis: revenue + orders)
  - Sales by Category (donut chart)
  - Regional Revenue vs Target (grouped bar)
  - Top Products by Revenue (ranked list)
- **🔽 Filters & Slicers** — Period (Q1–Q4), Region, Category, Customer Segment
- **📋 Transactions Table** — Live data table with status badges
- **🌙 Dark theme** — Clean, professional dark UI

## Tech Stack

| Tool | Purpose |
|------|---------|
| HTML / CSS / JS | Frontend (no framework needed) |
| [Chart.js 4.4](https://www.chartjs.org/) | All charts |
| [PapaParse](https://www.papaparse.com/) | CSV parsing |
| GitHub Pages | Free hosting |

## File Structure

```
sales-dashboard/
├── index.html           # Complete dashboard (single file)
├── README.md            # This file
└── sample-data/
    └── sales_sample.csv # Test with this file
```

## How to Run Locally

Just open `index.html` in any browser — no server needed.

## How to Deploy on GitHub Pages

See the step-by-step guide in the next section ↓

## Sample CSV Format

```
date,product,region,amount,category
2024-01-05,Pro Laptop,North,2399,Electronics
2024-01-08,Smart Watch,East,349,Electronics
2024-01-10,Running Jacket,South,89,Apparel
```

---

*Built as part of Thiranex Internship Program*
