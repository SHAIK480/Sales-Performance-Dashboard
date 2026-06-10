# Sales Performance Analysis Dashboard
### Power BI | Data Analyst Assessment Project

---

## Overview

An end-to-end business intelligence solution built as part of a Data Analyst assessment. The goal was to transform raw sales data into an interactive dashboard that enables stakeholders to monitor performance, track targets, and identify regional and customer-level trends.

---

## Dashboard Pages

### 1. Executive Overview
- Total Sales, Total Orders, and key Customer Metrics
- High-level KPIs for leadership decision-making

### 2. Regional Analysis
- Sales breakdown by region
- Regional contribution comparison
- Period-over-period trend analysis

### 3. Target vs. Actual Performance
- Sales target tracking with variance analysis
- YoY (Year-over-Year) performance evaluation

### 4. Customer Insights
- Customer-level revenue contribution
- Order distribution and buying patterns

---

## Screenshots

## Dashboard Preview

### Sales Performance Dashboard
![Sales Performance Dashboard](Screenshots/Sales_Performance_dashboard.png)

### Regional Performance
![Regional Performance](Screenshots/Regional_Performance.png)

### Returns & Delays
![Returns & Delays](Screenshots/Returns&Delays.png)

### Key Insights
![Key Insights](Screenshots/Key_Insights.png)

## Data Model
![Data Model](Screenshots/Data-Model_view.png)

---

## Data Model

Built on a **star schema** with fact and dimension tables connected through a purpose-built **Date Table** to support accurate time intelligence in DAX.

Key modeling decisions:
- Resolved Many-to-Many relationships using a bridge/composite key approach
- Set correct cross-filter directions to avoid ambiguous relationships
- Used a calculated Date Table to enable YoY and period comparison measures

---

## DAX Measures

Key measures developed:
- `Total Sales` — base aggregation measure
- `Total Orders` — distinct order count
- `YoY Sales Growth %` — year-over-year variance using time intelligence
- `Sales vs Target Variance` — absolute and percentage gap against targets

---

## Tools & Skills

| Area | Tools / Concepts |
|---|---|
| Data Cleaning | Power Query (M language) |
| Data Modeling | Star Schema, Relationships, Date Table |
| Calculations | DAX (time intelligence, KPIs, variance) |
| Visualization | Power BI Desktop |
| Design | Multi-page report, slicers, cross-filtering |

---

## Repository Structure

```
📁 sales-performance-dashboard/
├── README.md                 # Project documentation
└── screenshots/              # Dashboard page screenshots
    ├── executive-overview.png
    ├── regional-analysis.png
    ├── target-vs-actual.png
    └── customer-insights.png
```

---

## Notes

- The **dataset is not included**
- The daashboards are made using Power BI - [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
- All DAX measures and data model design are original work.

---

## Author

**Mohammad Maheer Shaik**  
B.Tech CSE | RGUKT (IIIT) Nuzvid  
[LinkedIn](https://www.linkedin.com/in/mohammad-maheer-shaik-9a517b252/) • [GitHub](https://github.com/SHAIK480)
