# 🌿 ESG & Financial Performance Dashboard (Fortune 500 — 2021)

![Banner](assets/banner_esg_finperf.png)

**Goal:** Explore whether higher ESG performance aligns with profitability and valuation.

## 🔎 What’s inside (no PBIX)
- `visuals/` – **PDF & screenshots only** (no .pbix published)
- `reports/clean_panel_powerbi.csv` – dataset loaded into Power BI
- `analysis/ESG_FinPerf_BEST.ipynb` – methods & OLS summaries
- `LICENSE` – MIT (code); see note below for visuals

## 📊 Key Results
- **Avg ESG**: 62.41  
- **Avg ROA**: 0.09  
- **Avg P/B**: 6.40  
- **ESG–ROA correlation**: –0.14 (weak negative)  
- **Total market cap** (72 firms): ~$4T  
- **Top ESG sector**: Industrial Conglomerates (75.35)  
- **Top ROA sector**: Trading Companies & Distributors (0.18)

## 🧮 Methods
- Python (pandas, statsmodels, yfinance)
- OLS with HC3 robust SE, sector fixed effects
- Winsorization on key metrics
- Power BI for data stories (exported as PDF/PNG only)

## 📂 How to view
Open `visuals/ESG_Dashboard_Overview.pdf` and the PNG screenshots in `visuals/`.

## 🧑‍💻 Author
**Daniel Sibanda** – MBA (Business Systems & Analytics)  
LinkedIn: https://www.linkedin.com/in/daniel-sibanda-554b40165/ • GitHub: [DanielSibanda](https://github.com/DanielSibanda)

## ⚖️ License
- **Code**: MIT (see `LICENSE`)
- **Visuals** (PDF/PNG in `visuals/`): *(Optional)* CC BY-NC 4.0 — non-commercial use with attribution.

