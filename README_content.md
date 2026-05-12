## Supply Chain Portfolio – Dhaval Vaghela

### Simulation 4 – Canadian Fabricated Metal Manufacturing Analysis

[View Live Dashboard](https://dhavalpvaghela96-coder.github.io/supply-chain-portfolio/SIM4_Dashboard_v2.html)

Independent industry analysis using Statistics Canada data (NAICS 332, 2015–2025).
Covers demand shock, post-COVID recovery, capacity strain, root cause and recommendations.

---

## Canadian Fabricated Metal Manufacturing
### Supply Chain Demand Analysis: 2015 to 2025

**Independent Industry Analysis | Production Planning Context**
Prepared by: Dhaval Vaghela | May 2026

---

## Executive Summary

This analysis looks at demand patterns in Canadian fabricated metal manufacturing between 2015 and 2025 using Statistics Canada data. The data shows that after COVID, demand came back much faster and higher than before. New orders jumped 23% in a single year and unfilled orders climbed a billion dollars above pre-COVID levels and stayed there. The key question this raises for production planning is whether the replenishment logic kept up with that shift, or whether the entire supply chain was simply too overwhelmed to respond in time.

---

## Data Source

**Source:** Statistics Canada, Table 16-10-0047-01 — Manufacturers' Sales, Inventories and Orders by Industry

- Industry filter: Fabricated metal product manufacturing [NAICS 332]
- Adjustment filter: Unadjusted raw monthly values
- Date range: January 2015 to December 2025
- Units: Canadian dollars reported in thousands
- Working dataset: 1,188 rows covering shipments, new orders, unfilled orders, WIP, finished goods and inventory ratios

---

## Findings

### 1. The COVID Shock in 2020

The fabricated metal sector saw a sharp drop across all three metrics in 2020. New orders fell the hardest at 46.8% because customers stopped placing orders almost immediately when lockdowns hit. Sales dropped 39.8%, while unfilled orders only fell 18.3%, meaning manufacturers still had a large backlog to work through even as new demand dried up.

| Metric | 2019 Baseline | 2020 COVID Low | 2022 Peak | Drop % | Recovery % |
|---|---|---|---|---|---|
| Sales (Shipments) | $3.76B | $2.26B | $4.89B | 39.8% | +115.8% |
| New Orders | $3.91B | $2.08B | $5.30B | 46.8% | +155.2% |
| Unfilled Orders | $7.10B avg | $6.63B avg | $8.11B avg | 18.3% | +43.6% |

---

### 2. Post-COVID Recovery

After lockdowns lifted, orders did not come back slowly. They surged. In 2021 alone, new orders grew 23% compared to the year before. By 2022 they had gone past pre-COVID levels entirely. This was not a gradual recovery. It was a sudden jump that hit the entire industry at once.

- New orders grew 23.2% year-on-year in 2021, the single largest annual jump in the dataset
- Sales grew 18.7% in 2021 and a further 19.1% in 2022
- By 2022 new orders had reached $5.30B, which is 36% above the 2019 pre-COVID baseline of $3.91B

---

### 3. The Backlog Never Cleared

Average unfilled orders in 2022 and 2023 settled at around $8.1B, which is $1 billion above the 2019 baseline of $7.1B. Even as manufacturers processed record order volumes, the backlog kept growing. The unfilled-to-new-orders ratio stayed above 1.8 through 2023, meaning for every dollar of new orders coming in, there was still $1.80 sitting in the backlog waiting to be fulfilled.

| Year | Avg New Orders | Avg Unfilled Orders | Avg Sales | Ratio | YoY Growth |
|---|---|---|---|---|---|
| 2019 | $3,452M | $7,098M | $3,460M | 2.06x | — |
| 2020 | $3,033M | $6,631M | $3,065M | 2.19x | 12.1% |
| 2021 | $3,738M | $6,903M | $3,637M | 1.85x | +23.2% |
| 2022 | $4,383M | $8,109M | $4,333M | 1.85x | +17.3% |
| 2023 | $4,481M | $8,104M | $4,546M | 1.81x | +2.2% |

---

## Root Cause

The data shows persistent backlogs that never fully cleared even as manufacturers processed record order volumes. This suggests the bottleneck was not just internal planning.

- When demand surges across an entire industry at once, suppliers upstream face the same pressure. Raw materials, components, shipping -- everything gets strained at the same time.
- Even a well-run manufacturer trying to react quickly would have faced delays they could not control. The strain was industrywide, not company-specific.
- The post-COVID demand surge was not gradual. A 23% year-on-year jump is a step change that no planning system with a historical lag can fully anticipate.

---

## Recommendations

Based on what the data shows, a few things are worth reviewing:

- Check whether current reorder points reflect post-2021 demand levels or are still based on quieter periods. The demand floor has shifted and planning parameters should reflect that.
- When building supplier lead time assumptions, account for the fact that industrywide backlogs put pressure on suppliers too. Pre-COVID lead times may no longer be realistic.
- A regular review of demand trends would help catch shifts early before they create floor-level shortages. Quarterly is a reasonable starting point.

---

## Limitations

- This dataset covers the whole industry at a national level. It does not show what happened inside any specific company or which product categories were most affected. That level of detail would need internal company data.
- Industry-wide trends do not tell the full story for any single manufacturer. A company's specific customers, suppliers, and product mix could mean their experience looked very different from the national average shown here.

---

## Conclusion

The data tells a clear story. Demand in Canadian fabricated metal manufacturing came back faster and harder than the drop that came before it. Unfilled orders stayed elevated for years, which points to a supply chain that was collectively stretched, not just individual companies making poor planning decisions.

This analysis does not have all the answers. It does not show what happened inside any specific company or why individual decisions were made. What it does show is the industrywide environment that every production planner in this sector was operating in between 2021 and 2023. Understanding that context is the starting point for better planning decisions going forward.

---

*Data Source: Statistics Canada, Table 16-10-0047-01 | Analysis Period: 2015 to 2025 | Prepared: May 2026*
