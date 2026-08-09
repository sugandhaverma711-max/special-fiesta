# Year-over-Year Revenue & Profitability Growth Analysis

Power BI project analyzing multi-year sales data to calculate year-over-year (YoY) revenue growth, profit margin, and top-performer rankings using time-intelligence DAX.

## Overview

This project was built as hands-on practice for the **Microsoft Power BI Data Analyst Professional Certificate** (Coursera), with a focus on time-intelligence DAX techniques and translating quantitative trends into a written business summary.

> **Note:** This project uses a sample sales dataset for practice purposes, not proprietary or client data.

## Tools & Techniques

- **Power BI Desktop** — data modeling, visualization
- **DAX** — time-intelligence functions (`SAMEPERIODLASTYEAR`, `DATEADD`), ranking (`TOPN`), variables (`VAR`/`RETURN`)
- **Data visualization** — KPI cards, clustered column charts

## Key DAX Measures

| Measure | Purpose |
|---|---|
| Revenue YoY % | Year-over-year revenue growth using `SAMEPERIODLASTYEAR` |
| Profit Margin | `DIVIDE(Profit, Revenue)` |
| Top 3 Salespersons | Performer ranking using `TOPN` |
| Sales Comparison | Period-over-period comparison using `DATEADD` |

## Key Findings

- Revenue grew significantly between 2017–2019 (~86% increase)
- A sharp decline (~50%) followed between 2019–2020
- Overall multi-year growth was ~21%
- Profit margin remained thin at ~1.31%, highlighting a gap between revenue growth and profitability

## Dashboard Preview

![dashboard](dashboard_screenshot)

## Files

- `YOY_and_Growth_analysis.pbix` — Power BI report file (open in Power BI Desktop to explore interactively)
