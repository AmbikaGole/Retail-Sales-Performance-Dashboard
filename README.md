# Retail Sales Performance Dashboard

**Why is the West region underperforming, and where should management look first?**

An interactive **Power BI** dashboard analysing **100,000 retail transactions ($138M in sales, 2021–2025)** across sales departments, customer types and product categories.

> **Bottom line:** South Region generated **$36M** versus West Region's **$9M**, a **$27M gap**. Product mix is the first place to look; local competition and supply-chain delays are the next hypotheses to test.

![Dashboard overview](Images/dashboard_overview.png)



## Key Findings

| | Finding | Evidence |
|---|---|---|
| 1 | **West Region is the weakest performer** | $9M vs South Region's $36M, a **$27M gap** (4x the sales) |
| 2 | **B2B customers drive revenue** | Wholesale ($43M) and Corporate ($32M) are the top customer types |
| 3 | **Sales are concentrated in one category** | Miscellaneous products = $81M; Furniture = only $3M |
| 4 | **Credit dominates and is growing** | Credit sales consistently exceed cash sales across 2021–2025 |

### The regional gap
![Total sales by department, South vs West](Images/regional_gap.png)

---

## Recommendations
- **Diagnose the West Region first.** Compare its product mix against the South Region to find gaps
- **Prioritise B2B channels** (Wholesale and Corporate) for growth
- **Review category strategy**: test whether low-performing categories like Furniture should be expanded or rationalised
- **Next step:** add external market data (local competition, supply-chain performance) to move from *where* the gap is to *why*



##  Methodology
- **Data cleaning and transformation** in Power Query
- **DAX calendar table** for time-intelligence analysis:

![DAX date table](Images/dax_date_table.png)

- Performance benchmarking across **sales departments, 5 customer types** (Wholesale, Corporate, Retail, Online, VIP) and **7 product categories**
- Root-cause framing of the regional performance gap

##  Limitations
The dashboard identifies **where** the gap is, but not yet **why**. Confirming root causes would require external data such as local competitor presence and supply-chain lead times.

## Tools
Power BI · Power Query · Tableau · DAX · Microsoft Excel

*Academic project, Master of Business Analytics, Macquarie University.*
