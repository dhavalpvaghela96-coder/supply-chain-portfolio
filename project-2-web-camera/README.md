# Web Camera Late Delivery Risk Investigation
## DMAIC-Based Inventory Analysis

**Dhaval Vaghela** | Mechanical Engineer | Supply Chain Management Graduate | Six Sigma Yellow Belt

---

&nbsp;

[![View Live Dashboard](https://img.shields.io/badge/View%20Live%20Dashboard-%233b82f6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://dhavalpvaghela96-coder.github.io/supply-chain-portfolio/project-2-web-camera/SIM2_Dashboard.html)

&nbsp;

---

## What This Project Is About

Out of 50 product categories in a wholesale distributor dataset, Web Camera stood out as the biggest business risk. It had the highest revenue among the top 5 late delivery risk categories, with 58% of its orders at risk of late delivery. This project uses DMAIC — a Six Sigma methodology — to find the root cause and recommend a fix.

---

## Project Details

| | |
|---|---|
| **Data Source** | DataCo Smart Supply Chain Dataset, Kaggle |
| **Industry** | Wholesale distribution, sporting and electronics goods |
| **Date Range** | January 2015 to January 2018 |
| **Dataset Size** | 180,519 order transactions, 118 unique products |
| **Tools Used** | Excel, Power Query, Pivot Tables, ABC Classification, Ishikawa Diagram |
| **Methodology** | DMAIC - Define, Measure, Analyze, Improve, Control |
| **Certification Applied** | ASQ Six Sigma Yellow Belt |

---

## Key Finding

Only 7 out of 118 products drive 76.87% of total revenue. Web Camera is a B item contributing $240,496 in revenue, yet it carries a 58% late delivery risk. The root cause is the absence of a reorder point for the camera SKU. Stock runs out before anyone notices and there is no trigger to reorder. This is compounded by long overseas supplier lead times. The fix requires setting a reorder point calibrated to the actual supplier lead time, not pre-COVID historical averages.

---

## DMAIC Summary

| Phase | What Was Done |
|---|---|
| **Define** | Identified Web Camera as highest revenue product among top 5 late delivery risk categories. Built SIPOC diagram. |
| **Measure** | ABC classification of 118 products. 7 A items drive 76.87% of revenue. Camera confirmed as B item with disproportionate risk. |
| **Analyze** | Ishikawa diagram mapped 12 root causes across 6 categories. Primary cause: no reorder point set for camera SKU. |
| **Improve** | Calculated average daily demand at 0.53 units per day over 1,126 days. Built reorder point framework. |
| **Control** | Recommended weekly stock checks and monthly late delivery rate tracking. Target: below 20% within 6 months. |

---

## What Is Inside This Project

- Interactive dashboard with 5 sections - Overview, Define, Measure, Analyze, Improve and Control
- Excel workbook with ABC classification, Pareto chart, Ishikawa table, and demand calculations
- Written report covering all 4 DMAIC phases with tables and plain language findings

---

*Data: DataCo Smart Supply Chain Dataset: publicly available on Kaggle*
