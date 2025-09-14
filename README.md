=# Player Acquisition & Betting Insights (Excel Dashboard)

A compact analytics project that shows **where growth comes from** (channels & products), how **promo spend performs**, and **player quality** — built in Excel with Power Query, PivotTables, Slicers, and clean visuals.

## What’s inside

**Interactive dashboard (Excel)**
- `/dashboard/Player_Acq_Insights_Dashboard.xlsx`  
  Use slicers for **Signup_YearMonth**, **Acq_Channel**, **Gender** to filter all views.

**One-page PDFs (for quick review)**
- `/docs/Dashboard.pdf` – the full dashboard on one page  
- `/docs/Executive_Summary.pdf` – business findings & recommendations

**Screenshots**
- `/docs/screenshots/deposit_per_player.png` – Analyst KPI (table + chart)
- `/docs/screenshots/deposit_by_channel.png` – Deposits by acquisition channel
- `/docs/screenshots/bonus_vs_deposit.png` – Promo ROI by product
- `/docs/screenshots/signups_trend.png` – Monthly new signups trend

> Tip: PDFs are perfect for recruiters; Excel is there for hands-on reviewers.

---

## Dashboard KPIs

1. **Monthly New Signups** – seasonality & growth trend  
2. **Total First Deposit by Acquisition Channel** – who actually brings value  
3. **Average First Bet by Gender** – early bet quality  
4. **Bonus Cost vs Deposit by Product** – promo ROI  
5. **Analyst KPI:** **Deposit per Player** (₹ per player by channel)

---

## Key Findings (from this dataset)

- **Signups trend:** early peak then a steady decline through 2020–2021  
- **Deposit concentration:** NA & PPC drive the largest deposit totals; long-tail channels are small  
- **First-bet quality:** F segment slightly higher first bet vs. M  
- **Promo ROI by product:** SportsBook deposits > bonus cost (healthy). eGaming bonus cost > deposits → likely inefficient.

---

## Recommendations

- **Shift promo** from eGaming toward SportsBook; A/B test lower bonus % or stricter rollovers in eGaming  
- **Channel mix:** Favor PPC / NA; squeeze or pause Display/Email/Programmatic if CAC/LTV doesn’t justify spend  
- **Segment plays:** Test female-targeted onboarding (creative + first-bet boost)  
- **Weekly KPI cadence:** Deposits by Channel, Bonus:Deposit ratio by Product, Avg First Bet, New Signups

---

## How it was built (method)

- Clean merge in **Power Query** (Players, First Deposit, First Bet, Activity, Bonus Cost)  
- Standardized datatypes, created **Signup_YearMonth**, handled nulls  
- **PivotTables + Slicers** for interactive views  
- **Calculated fields** (where appropriate) and a helper **Player_Flag** for stable counts  
- Light **conditional formatting** and chart polish for readability


## How to View
- Open `/docs/dashboard.pdf` for a quick overview  
- Open `/docs/executive_summary.pdf` for business findings & recommendations  
- Use `/dashboard/Player_Acq_Insights_Dashboard.xlsx` for the interactive Excel dashboard  


