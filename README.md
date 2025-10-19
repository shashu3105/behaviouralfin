# Investor Archetypes — Oxford Risk (Python)

This repo reproduces a clean investor–archetype workflow on the **Oxford Risk** sample data:  
**K-means clustering → cluster profiles → PCA map → trait–wealth associations**.  
Data are **omitted (or synthetic)** for privacy; the code runs if you drop in two CSVs:

- `data/personality.csv` — columns: `_id, confidence, risk_tolerance, composure, impulsivity, impact_desire`
- `data/assets.csv` — columns: `_id, asset_allocation, asset_currency, asset_value, created`


