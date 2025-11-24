# Investment Portfolio Circle Packing Visualization

Email: **24f1000881@ds.study.iitm.ac.in**

This repository contains a Circle Packing visualization created using **RAWGraphs** to represent a diversified investment portfolio across multiple sectors and individual assets.

## Business Context

Rutherford Rutherford and Mann is a strategic consulting firm specializing in advanced data visualization and business intelligence solutions. The client required a publication-ready visualization for:

- Annual report
- Board presentations
- Strategic planning documents

Traditional bar and pie charts were not sufficient to show:
- Hierarchical structure (sector → asset)
- Relative allocation (investment size)
- Diversification and risk exposure across sectors

Circle Packing was chosen as the most appropriate visualization to communicate portfolio diversification and risk management.

## Data Structure

The dataset encodes three fields:

- `sector` – Investment sector (e.g., Technology, Healthcare, Finance, Energy)
- `asset` – Individual asset / company within the sector (e.g., Apple, Pfizer)
- `investment` – Amount invested in that asset (in monetary units)

Example rows:

```csv
sector,asset,investment
Technology,Apple,12450000
Technology,Microsoft,11230000
Healthcare,Pfizer,7340000
Energy,ExxonMobil,6360000
Finance,Bank of America,7125000
