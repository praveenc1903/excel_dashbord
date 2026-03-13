# 📊 Excel Data Analytics Portfolio

A hands-on collection of Excel workbooks and datasets covering core data analyst skills — from data cleaning and formulas to interactive dashboards.

---

## 📁 File Overview

| File | Skill Area | Description |
|------|-----------|-------------|
| `Conditional Formatting Excel.xlsx` | Visualisation | Rules-based cell highlighting for quick pattern detection |
| `Data Cleaning Excel.xlsx` | Data Quality | Techniques for handling nulls, duplicates, and inconsistencies |
| `Excel Charts.xlsx` | Visualisation | Chart types and best practices for data storytelling |
| `Formula Excel.xlsx` | Analytical Functions | Core formulas: IF, INDEX/MATCH, aggregations, nested logic |
| `pivot table.csv` | Data Aggregation | Source data used to build and explore PivotTables |
| `XLOOKUP, VLOOKUP.xlsx` | Lookup Functions | Side-by-side comparison of VLOOKUP vs the modern XLOOKUP |

---

## 🚲 Featured Project: Bike Sales Dashboard

An end-to-end Excel dashboard analysing customer purchasing behaviour across demographic segments.

### Dashboard Panels

| Panel | Chart Type | Key Insight |
|-------|-----------|-------------|
| **AVG Income by Gender** | Clustered Bar | Males who purchased bikes earn ~$5K more on average than non-buyers |
| **Customer Age Brackets** | Line Chart | Middle-aged customers are the primary buyers (52 vs 35 non-buyers) |
| **Customer Commute Distance** | Line Chart | Purchases peak at 1–2 miles; drop sharply beyond 5 miles |
| **Age Distribution** | Horizontal Bar | Ages 26–31 show the highest purchase density |

### Slicer Filters Available
- **Education** — Bachelors / Graduate Degree / High School / Partial College / Partial High School
- **Gender** — Female / Male
- **Marital Status** — Married / Single
- **Age** — Individual year filtering (25–31+)

### Key Metrics (Unfiltered)
| Segment | Avg Income (No Bike) | Avg Income (Purchased) |
|---------|---------------------|----------------------|
| Female | $40,483 | $43,333 |
| Male | $45,573 | $40,571 |

---

## 🛠️ Skills Demonstrated

- **PivotTables & PivotCharts** — summarising raw CSV data into interactive panels
- **Slicers** — cross-filtering multiple charts from a single click
- **XLOOKUP / VLOOKUP** — dynamic lookups across datasets
- **Conditional Formatting** — heatmaps, data bars, and rule-based highlights
- **Data Cleaning** — deduplication, standardisation, null handling
- **Charting** — bar, line, and horizontal bar charts with dual-series comparisons

---

## 🚀 Getting Started

1. Open `pivot table.csv` to explore the raw dataset
2. Follow `Data Cleaning Excel.xlsx` to understand pre-processing steps
3. Review `Formula Excel.xlsx` and `XLOOKUP, VLOOKUP.xlsx` for the analytical logic
4. Open the Bike Sales Dashboard workbook to interact with the final output using slicers

---

## 💡 Notes

- All files use **Microsoft Excel** (`.xlsx` / `.csv` format); compatible with Excel 2016+
- XLOOKUP requires **Excel 2019 / Microsoft 365** — use VLOOKUP as fallback on older versions
- The dashboard is driven by a PivotTable connected to `pivot table.csv`

---

*Built as part of a data analytics learning portfolio — covering the full Excel workflow from raw data to interactive dashboard.*
