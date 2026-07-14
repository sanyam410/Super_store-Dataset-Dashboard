# 📊 Superstore Sales Performance Dashboard

`A Power BI dashboard analyzing sales, profit, and delivery performance across the Superstore retail dataset.`

[![Tool: Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811.svg)](https://powerbi.microsoft.com/)
[![Dataset: Superstore](https://img.shields.io/badge/Dataset-Superstore%20Sales-blue.svg)](#-the-data)

## 📜 Project Overview

This dashboard explores the Superstore Sales dataset — orders, products, and customers
across the US — to answer a simple retail question: **where is the business winning,
and where is it losing money?** It combines top-line KPIs, category and sub-category
breakdowns, regional performance, and year-over-year trends into a single view.

## 🗺️ Table of Contents

- [📜 Project Overview](#-project-overview)
- [📦 The Data](#-the-data)
- [🖼️ Dashboard Preview](#️-dashboard-preview)
- [✨ What's on the Dashboard](#-whats-on-the-dashboard)
- [🚀 Getting Started](#-getting-started)
- [📋 Notes & Next Steps](#-notes--next-steps)
- [📄 License](#-license)

## 📦 The Data

| | |
|---|---|
| **Source** | Superstore Sales Dataset |
| **Grain** | Individual order line |
| **Key fields** | Sales, Profit, Quantity, Category, Sub-Category, Ship Mode, Segment, Region, Payment Mode, State, Order Date, Avg. Delivery Time |

## 🖼️ Dashboard Preview

![Dashboard Overview](outputs/[FILL IN filename].png)



## ✨ What's on the Dashboard

**KPI Cards** — Sales, Profit, Quantity, and Avg. Delivery Time at a glance.

**Category Performance** — clustered bar charts breaking down Sales by Category,
Sub-Category, and Ship Mode, to spot which product lines and fulfillment methods drive
the most revenue.

**Trends Over Time** — area charts tracking Sales and Profit year-over-year, to see
whether revenue growth is actually translating into profit growth.

**Geography** — a state-level map plotting Sales and Profit together, to spot regions
that sell well but aren't necessarily profitable.

**Customer & Order Mix** — donut charts breaking down Sales by Segment, Region, and
Payment Mode.

**Filtering** — a Region slicer lets you narrow every visual on the page down to a
specific part of the country.


## 📋 Notes & Next Steps

This is an early version of the dashboard. A few things worth improving next:

- Add a date range slicer alongside the existing Region slicer, so the time-based
  charts can be filtered as well as the categorical ones
- Add a header/title text box so the dashboard is self-explanatory as a standalone
  screenshot
- Consider combining the Sales and Profit area charts into a single dual-axis view to
  make the growth-vs-profitability comparison more direct
- Rename the report page from its default name to something descriptive (e.g. "Overview")

## 📄 License

This project is licensed under the MIT License.
