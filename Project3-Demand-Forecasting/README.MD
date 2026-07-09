# Project 3 :- Demand Forecasting and Reorder Point Planning

[![View Project](https://img.shields.io/badge/🔗-VIEW%20PROJECT-297ef2?style=for-the-badge)](https://docs.google.com/spreadsheets/d/1Gpso31yG27oFcwR4VHd18rR0UakTIPEN/edit?usp=sharing)


## What This Project Is About

I took 2 years of daily retail sales data (73,100 rows, 5 stores, 20 products) and used it to forecast future demand, calculate how much buffer stock each product needs, and figure out at what inventory level a new order should be triggered.

## Why I Built This

My first two projects were backward-looking, they explained what already happened. This one is forward-looking.

## Dataset

- Source: Retail Store Inventory Forecasting Dataset (Kaggle)
- 73,100 rows, daily sales from January 2022 to January 2024
- 5 stores, 20 products across Groceries, Electronics, Clothing, Furniture, and Toys
- One assumption made: lead time per category, since the dataset does not include supplier lead time data. Values used are based on typical industry lead times and are documented in the Lead Time Assumptions tab.

## What I Did


Lead Time Assumptions:** Documented the one assumption in the project i.e. lead time per category (Groceries 5 days, Electronics 18 days, Clothing 15 days, Furniture 25 days, Toys 18 days).

Demand Forecast:** Added up daily sales into 104 weekly totals per product using SUMIFS. Used FORECAST.LINEAR to project week 105 demand for all 5 products.

Safety Stock and Reorder Point:** Calculated safety stock using the Z-score method at 95% service level. Calculated reorder point as average weekly demand × lead time + safety stock.

Scenario Test:** Tested what happens if actual demand comes in 20% above or below forecast. All 5 products showed low stockout risk at current safety stock levels.

Dashboard:** Summary table, chart comparing average weekly demand vs week 105 forecast, and key findings.

## Key Findings

- Weekly demand across all 5 categories averaged between 850 and 1,000 units with no upward or downward trend over 2 years
- Electronics had the highest demand variability, Groceries the most stable
- Reorder points ranged from 1,091 units (Groceries) to 4,434 units (Furniture), driven mainly by lead time difference
- All 5 products can absorb a 20% demand spike without running out of stock at current safety stock levels

## Tools Used

Excel, Power Query, SUMIFS, FORECAST.LINEAR, STDEV, IF

## View the File

[Open in Google Sheets](https://docs.google.com/spreadsheets/d/1Gpso31yG27oFcwR4VHd18rR0UakTIPEN/edit?usp=sharing)
