# Sales Performance Analytics — Portfolio Project

## Business Question
Why do revenue and profit diverge across product categories, 
and which products should be prioritized or discontinued?

## Dataset
- Superstore Sales (Kaggle)
- 9,994 orders · 4 regions · 3 categories · 2011–2014

## Tools
| Tool | Purpose |
|------|---------|
| DuckDB (SQL) | KPI queries, loss-product identification |
| Python (pandas, seaborn) | EDA, feature engineering, visualization |
| Power BI | Executive dashboard |

## Key Findings
1. Revenue grew 4x from 2011 to 2014 — Q4 strongest every year
2. Technology leads revenue but has compressed profit margin
3. Cubify CubeX 3D Printer operates at -80% profit margin
4. Tables sub-category has 4 of the top 10 loss-making products
5. Canon & Fellowes dominate profitable products in Office Supplies

## Recommendations
- Discontinue or reprice Cubify CubeX line → recover ~$12,720/year
- Cap discounts on Tables sub-category → recover ~$8,000–10,000/year
- Increase investment in Office Supplies segment

## Project Structure
├── 01_eda.ipynb              # Data loading, cleaning, EDA
├── 02_sql_analysis.py        # DuckDB SQL queries
├── outputs/                  # CSV exports for Power BI
├── dashboard.pbix            # Power BI dashboard file
└── README.md

## Dashboard Preview
<img width="1961" height="1101" alt="image" src="https://github.com/user-attachments/assets/42cd4aad-2677-41f2-9fdf-0fcb9e4e54b5" />


## Author
Muhammad Irfan Karim
```

---

## Phase 6 selesai ✅ — Project complete!
```
✅ Phase 1 — Project brief
✅ Phase 2 — EDA & data quality
✅ Phase 3 — SQL + Python analysis  
✅ Phase 4 — Power BI dashboard
✅ Phase 5 — AI insight validation
<!-- ✅ Phase 6 — Project story & deliverables -->
