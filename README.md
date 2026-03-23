# Business Sales Performance Analytics Dashboard

**Internship Project — Task 1 of 3**  
Future Interns | Data Science Track | March 2025

---

## 📊 Project Overview

Built an interactive **Power BI dashboard** analyzing **$9.7M in UK e-commerce revenue** across **38 countries** from July–December 2011.

This was my first real-world data analytics project — connecting real Excel data, building DAX measures, and creating actionable business insights.

---

## 📁 Files in this repo

- **Sales_Data_MutasimAhmed.xlsx** — Raw transaction data (5,200+ records, 3 sheets)
  - `Sales_Data` — All transactions with InvoiceNo, Quantity, UnitPrice, Revenue, Date, Country, TransactionType
  - `KPI_Summary` — Live summary metrics (formulas connected to Sales_Data)
  - `Monthly_Revenue` — Monthly breakdown
  
- **Dashboard_PowerBI_MutasimAhmed.png** — Screenshot of the final Power BI dashboard

- **DAX_Measures_PowerBI_MutasimAhmed.docx** — All DAX code (calculated columns + measures)

- **task_1.pbix** *(coming soon)* — The actual Power BI Desktop file (download to open in Power BI)

---

## 🎯 Key Findings

✅ **Total Revenue:** $9,726,201  
✅ **Total Quantity:** 5.16M units sold  
✅ **Cancellation Rate:** 1.85%  
✅ **Average Unit Price:** $1.88  
✅ **Top Country:** UK (84% of revenue)  

### Major Insights

1. **Thursday is the strongest day** — $2.1M weekly average (25% above weekly avg)
2. **Peak buying window:** 10am–12pm UTC (24% of daily transactions)
3. **International is underserved** — Only 16% of revenue (growth opportunity)
4. **December spike** — $1.45M peak (seasonal demand pattern)
5. **Top products:** REGENCY, POSTAGE, PAPER dominate by revenue

---

## 🛠 Tools Used

- **Microsoft Excel** — Data cleaning, summary tables
- **Microsoft Power BI Desktop** — Dashboard, visuals, DAX measures
- **GitHub** — Version control & portfolio showcase

---

## 📖 How to view the dashboard

### Option A: Live in Power BI Desktop (Interactive)
1. Download **task_1.pbix** (once uploaded)
2. Open in Power BI Desktop
3. Full interactivity — slicers, drill-downs, filters

### Option B: Static screenshot (Quick preview)
1. View **Dashboard_PowerBI_MutasimAhmed.png** in this repo

### Option C: Explore the raw data
1. Open **Sales_Data_MutasimAhmed.xlsx**
2. 3 sheets ready to pivot/analyze

---

## 📈 Dashboard Features

| Visual | Purpose |
|--------|---------|
| **KPI Cards** | Total Revenue, Quantity, Avg Price, Cancellation Rate |
| **Monthly Revenue Trend** | Sales performance over 6 months |
| **Revenue by Day of Week** | Which days drive the most sales |
| **Top 20 Products** | Best performers by revenue |
| **Cancellation by Month** | Churn patterns |
| **UK vs International** | Regional split (pie chart) |
| **Revenue by Hour** | Peak transaction windows |

**Slicers:** Revenue Band, Transaction Type, Country, Date Range

---

## 🧮 DAX Measures Included

**KPIs:**
- Total Revenue (sales only)
- Total Quantity
- Total Transactions
- Avg Unit Price
- Cancellation Rate

**Regional:**
- UK Revenue
- International Revenue
- UK Revenue %

**Calculated Columns:**
- Day of Week, Hour of Day, Month Name
- Country Group (UK vs International)
- Revenue Band (High/Medium/Low)

Full DAX code in **DAX_Measures_PowerBI_MutasimAhmed.docx**

---

## 💡 What I Learned

✓ Real e-commerce data pipeline  
✓ End-to-end analytics workflow  
✓ DAX formulas & measure design  
✓ Dashboard storytelling  
✓ KPI definition & business metrics  
✓ Time-series analysis  

---

## 📊 Data Source

**Dataset:** UCI Online Retail (Public Domain)  
**Period:** 1 July 2011 – 31 December 2011  
**Records:** 5,200+ transactions  
**Type:** UK-based giftware e-commerce  

**Data cleaning applied:**
- Removed nulls in critical columns
- Filtered test/invalid transactions
- Calculated derived fields (Revenue, Day of Week, Hour, etc.)
- Classified transaction types (Sale vs Cancellation)

---

## 🚀 Next Steps

**Task 2:** *(coming soon)*  
**Task 3:** *(coming soon)*

---

**Internship:** Future Interns — Data Science Track  
**Status:** Task 1 ✅ Complete  
**Date:** March 2025  
**Created by:** Mutasim Ahmed  
**Location:** UAE  

