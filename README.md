# canada-trade-analysis
Analyzing $1.4 trillion in Canadian trade flows (2019-2023) using UN Comtrade data — COVID impact, China dependency, and partner recovery
# Canada Trade Flows 2019–2023

Analysis of Canadian import and export data across six major trading partners 
using UN Comtrade data. The goal was to understand how COVID-19 disrupted 
trade relationships and whether those relationships recovered by 2023.

## Dataset

- Source: UN Comtrade Database (comtradeplus.un.org)
- Scope: Canada trade flows with USA, China, Germany, Japan, Mexico, UK
- Period: 2019–2023 (annual)
- Size: 94,000 rows after cleaning
- Classification: HS2 commodity codes

## Key Findings

Canada's trade with China grew 19.7% between 2019 and 2023 — despite 
sustained political pressure to reduce dependency on Chinese supply chains. 
Electrical machinery and mechanical equipment account for the bulk of that 
import volume, neither of which has a short-term substitute supplier.

Mexico saw the steepest COVID shock in 2020 at -19.4%, driven by automotive 
supply chain shutdowns. It recovered fully by 2022.

The UK is the only major partner still below 2019 trade levels by 2023, 
down 16.5%. The data suggests Brexit created a structural reduction in 
Canada-UK trade that has not corrected over four years.

## Tools

Python (pandas, matplotlib) — data cleaning and analysis  
Power BI — dashboard  
UN Comtrade API — data source

## Files

`lab2.ipynb` — full analysis notebook  
`canada_trade_analysis.png` — four-panel visualization  
`data/` — cleaned CSVs exported from notebook
