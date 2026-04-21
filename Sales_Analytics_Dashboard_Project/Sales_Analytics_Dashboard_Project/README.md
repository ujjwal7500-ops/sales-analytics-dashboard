# Sales Analytics Dashboard — Power BI Capstone Project

## Project Overview
A complete 4-page interactive Sales Analytics Dashboard built in Microsoft Power BI,
analyzing 2,000+ transactions across products, customers, and regions for 2023–2024.

---

## Files in This ZIP

| File | Description |
|------|-------------|
| `Sales_Analytics_Data.xlsx` | Main dataset (4 sheets: Sales, Products, Customers, Targets) |
| `DAX_Measures.txt` | All 30+ DAX measures — paste into Power BI |
| `PowerQuery_M_Code.txt` | Power Query M transformations for all 5 queries |
| `Step_By_Step_Build_Guide.txt` | Complete guide to build the .pbix from scratch |
| `Project_Documentation.pdf` | 5-page project documentation (submission ready) |
| `README.md` | This file |

---

## How to Build the Dashboard

### Prerequisites
- Microsoft Power BI Desktop (free download: https://powerbi.microsoft.com/downloads)
- Windows OS
- Sales_Analytics_Data.xlsx (included)

### Quick Start
1. Open Power BI Desktop
2. **Get Data** → Excel → select `Sales_Analytics_Data.xlsx`
3. Load all 4 sheets via Power Query (use `PowerQuery_M_Code.txt`)
4. Create DateTable and mark as date table
5. Build relationships (star schema)
6. Add all measures from `DAX_Measures.txt`
7. Follow `Step_By_Step_Build_Guide.txt` to build all 4 pages
8. Save as `Sales_Analytics_Dashboard.pbix`

---

## Dashboard Pages

| # | Page | Key Insights |
|---|------|-------------|
| 1 | Executive Summary | Revenue KPIs, trend line, region split, top products |
| 2 | Sales Deep Dive | Category matrix, product scatter, MoM waterfall |
| 3 | Customer & Region | Geographic map, segments, state treemap |
| 4 | Target Analysis | Actual vs target, achievement %, color flags |

---

## Data Model (Star Schema)

```
DateTable ──┐
            ├── Sales (Fact) ──── Products
Customers ──┘
```

---

## Tech Stack
- **Power BI Desktop** — Dashboard & visualization
- **Power Query (M)** — ETL & transformation
- **DAX** — KPIs, time intelligence, dynamic measures
- **Excel** — Raw data source

---

## Submission Checklist
- [x] ZIP file with all project files
- [ ] GitHub repository (public)
- [x] PDF documentation (Project_Documentation.pdf)
- [ ] Name, Roll Number, Batch on submission form

---

*Capstone Project | Deadline: April 21, 2026*
