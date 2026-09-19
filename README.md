# 🐟 Aquaculture Production & Species Performance Dashboard

<img width="959" height="475" alt="image" src="https://github.com/user-attachments/assets/5ad08379-b57d-4a8d-a0ca-177ff93b8e19" />

A Power BI dashboard analyzing farming systems, species performance, and production metrics across India's aquaculture sector — built as part of a broader data intelligence initiative covering Indian fisheries and aquaculture.

## 📊 Overview

This dashboard provides a single-page, high-level view of aquaculture production data, letting users explore performance by state, region, species, and water type. It is built on a flattened, single-table data model (**Farming Systems & Species**) optimized for clean Power BI imports.

## 🎥 Demo Video

Watch the **Aquabas Dashboard Demo Video** for a full walkthrough of the dashboard, its visuals, and how to use the slicers:

👉 [Aquabas Dashboard Demo Video](ADD_VIDEO_LINK_HERE)

## ✨ Key Features

- **KPI Cards** — Total States, Total Species, and other headline metrics at a glance
- **Interactive Map** — Geographic distribution of production across states/regions
- **Scatter Chart** — Relationship analysis between production metrics (e.g. temperature vs. profit)
- **Gauge Chart** — Performance against target/benchmark
- **Donut/Pie Chart** — Breakdown by category (e.g. water type or market status)
- **Clustered Column Chart** — Comparative production/profit view
- **Slicers** — Filter by State, Region, Species, and Water Type for drill-down analysis

## 📈 Metrics Covered

| Metric | Description |
|---|---|
| Total Production | Aggregate production volume |
| Total Species | Count of species tracked |
| Total States | Number of states covered |
| Average Price | Mean market price |
| Average Temperature | Mean water/farming temperature |
| Profit | Absolute profit figure |
| Profit Margin % | Profitability ratio |
| Market Status | Current market condition indicator |

## 🗂️ Data Model & Source Data

The dashboard is powered by a single Excel file included in this repository:

📁 [`farming and species (1).xlsx`](farming%20and%20species%20%281%29.xlsx)

- **Single flat table:** Farming Systems & Species
- **Dimensions:** State, Region, Species, Water Type, Market Status
- **Measures:** Total Production, Total Species, Average Price, Average Temperature, Profit, Profit Margin %
- Designed as one denormalized sheet (no relationships) for simplicity and fast loading

## 🛠️ Tech Stack

- **Power BI Desktop** — report authoring & data modeling
- **Excel** — source data preparation and cleaning

## 📥 Getting Started

1. Clone or download this repository
2. Keep `farming and species (1).xlsx` in the project folder
3. Open `dash.pbix` in Power BI Desktop
4. Refresh the data connection if prompted (point it to the Excel file if the path has changed)
5. Explore the dashboard using the slicers on the right panel

## 📌 Notes

- This is part of a set of dashboards under a larger **Multi-State Fisheries & Aquaculture Intelligence Platform**, alongside an **Executive KPI Dashboard** tracking agricultural market (mandi) prices.
- Data reflects **[add reporting period / source here]**.


