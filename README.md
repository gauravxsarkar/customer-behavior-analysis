# Customer Behaviour Analysis

**Author:** Gaurav Sarkar
**Dataset:** 3,900 customer records | 18 columns
**Tools:** PostgreSQL · Python (Pandas, Matplotlib, Seaborn) · Power BI

---

## Overview

An end-to-end data analytics project analysing customer shopping behaviour — covering SQL querying, Python EDA, and an interactive Power BI dashboard.

---

## Project Structure

```
├── customer_behaviour.pbix               # Power BI dashboard (4 pages)
├── customer_behaviour_analysis.sql       # 10 SQL business queries
├── customer_shopping_behaviour_analysis.ipynb  # Python EDA notebook
└── customer_behaviour_report.docx        # Full project report
```

---

## Key Questions Answered

- Which gender and age group drives the most revenue?
- Do subscribed customers spend more than non-subscribers?
- Which products have the highest ratings and discount rates?
- How does shipping type affect average purchase amount?
- How are customers segmented into New, Returning, and Loyal?

---

## SQL Highlights

- CTEs and window functions (`ROW_NUMBER() OVER PARTITION BY`) for product ranking
- Correlated subqueries for high-value discount user identification
- `CASE WHEN` segmentation for loyalty tiers

## Python EDA Highlights

- Purchase amount distribution, seasonal trends, gender/age analysis
- Seaborn heatmap for numerical feature correlations
- Review rating analysis by product

## Power BI Dashboard Pages

| Page | Focus |
|------|-------|
| 1 — Overview | KPI cards, avg spend by age group, revenue by season |
| 2 — Products | Top items, review ratings, color-season heatmap |
| 3 — Segments | Subscriber vs non-subscriber, discount impact, frequency |
| 4 — Logistics | Shipping preferences, payment methods, US state map |

---

## Key Findings

- Subscribers spend more on average → prioritise subscription conversion
- Repeat buyers (>5 purchases) are most likely to subscribe
- Senior and Adult segments generate the highest revenue
- Express shipping users have a slightly higher average order value
