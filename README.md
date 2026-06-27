# 🛒 Brazilian Olist E-Commerce Analytics — Executive Report

> **Data Period:** September 2016 – October 2018  
> **Analyst:** Pruthviraj Vikas Chavan  
> **Tools:** Microsoft Excel  
> **Domain:** E-Commerce | Marketplace Analytics | Strategic Intelligence

---

## 📌 Project Overview

A comprehensive, executive-grade analysis of the **Olist Brazilian e-commerce marketplace** — one of the most widely studied public e-commerce datasets in data analytics.

The analysis spans **99,441 orders**, **$16,008,872 in total revenue**, **27 Brazilian states**, and **8 relational data tables** — answering 25 analytical questions and generating 20 CEO-level strategic insights across 9 domains. Built entirely in Microsoft Excel.

---

## 📊 Key Metrics at a Glance

| KPI | Value |
|---|---|
| Total Orders | 99,441 |
| Total Revenue (GMV) | $16,008,872 |
| Average Order Value | $160.99 |
| Average Delivery Time | 12.6 days |
| On-Time Delivery Rate | ~97% |
| Customer Repeat Rate | <5% |
| Top State Revenue Share (SP) | ~37% |
| Credit Card GMV Share | ~73–76% |

---

## 📸 Dashboard

### Full Executive Dashboard
![Full Dashboard](assets/screenshots/dashboard_full.png)

---

### KPI Summary Cards
![KPI Cards](assets/screenshots/kpi_cards.png)

---

### Monthly Revenue Trend (Sep 2016 – Oct 2018)
![Monthly Revenue Trend](assets/screenshots/monthly_revenue_trend.png)

---

### Revenue by Customer State
![Revenue by State](assets/screenshots/revenue_by_state.png)

---

### Orders by Customer State
![Orders by State](assets/screenshots/orders_by_state.png)

---

### Top Categories by Revenue
![Top Categories](assets/screenshots/top_categories.png)

---

### Top Products by Revenue
![Top Products](assets/screenshots/top_products.png)

---

### Top Customers by Revenue
![Top Customers](assets/screenshots/top_customers.png)

---

### Payment Revenue Mix
![Payment Mix](assets/screenshots/payment_mix.png)

---

### Order Status Distribution
![Order Status](assets/screenshots/order_status.png)

---

## 🗂️ Repository Structure

```
olist-ecommerce-analytics/
│
├── assets/
│   └── screenshots/                    # All dashboard screenshots
│       ├── dashboard_full.png
│       ├── kpi_cards.png
│       ├── monthly_revenue_trend.png
│       ├── revenue_by_state.png
│       ├── orders_by_state.png
│       ├── top_categories.png
│       ├── top_products.png
│       ├── top_customers.png
│       ├── payment_mix.png
│       └── order_status.png
│
├── data/
│   └── README_data.md                  # Dataset source & download instructions
│
├── dashboard/
│   └── Olist_Executive_Dashboard.xlsx  # Full interactive Excel dashboard
│
├── reports/
│   └── Olist_Executive_Analytics_Report.pdf   # 15-page executive report
│
├── .gitignore
└── README.md
```

---

## 🛠️ Tools & Techniques

**Microsoft Excel — end to end.** No Python, no SQL, no BI tools.

| Technique | Used For |
|---|---|
| Power Query | Importing and cleaning 8 CSV tables |
| Data Modelling | Relating orders, customers, sellers, products, payments, reviews, geolocation |
| Pivot Tables | Aggregations across all analytical dimensions |
| Pivot Charts | Revenue trend, category bars, donut chart, status distribution |
| Slicers & Timelines | Interactive filtering by month, state, category, payment method, order status |
| Conditional Formatting | KPI card highlights and threshold indicators |
| VLOOKUP / Named Ranges | Cross-table lookups and calculated fields |
| Dashboard Layout | Single-sheet executive view: KPI band → chart band → filter band |

---

## 🔍 Analytical Domains Covered

1. **Sales Analysis** — Monthly trend, seasonality, day-of-week patterns, basket density
2. **Revenue Analysis** — AOV, GMV drivers, cancellation leakage, Black Friday spike
3. **Customer Analysis** — Repeat rate, LTV segmentation, the one-and-done problem
4. **Product & Category Analysis** — Pareto concentration, top SKUs, dead-weight categories
5. **Payment Analysis** — Credit card vs. Boleto mix, installment behaviour
6. **Geographic Analysis** — State-level revenue, SP/RJ dominance, North/Northeast gap
7. **Logistics & Delivery** — Delivery time variance, carrier bottlenecks, estimate padding
8. **Executive Insights** — 20 CEO-level findings with estimated GMV impact per action
9. **Strategic Recommendations** — Prioritised P1/P2/P3 action matrix with ROI

---

## 💡 Top 5 Critical Findings

### 1. The One-and-Done Customer Crisis
**95%+ of customers made exactly one purchase.** Olist is spending $15–$30 CAC per customer with almost no retention flywheel. A 5-point improvement in repeat rate = **+$800K incremental GMV/year**.

### 2. Geographic Revenue Fragility
**SP + RJ = ~50% of GMV** despite being ~32% of Brazil's population. The North and Northeast — 30%+ of Brazil's geography — represent a **$2–$4M untapped GMV opportunity**.

### 3. Logistics is the Experience Killer
**12.6-day average delivery** masks extremes — Northern states average **20–25 days**. Delivery windows are padded 5–10 days beyond actual performance, destroying pre-purchase conversion rates.

### 4. Boleto Abandonment Locks Inventory
Boleto's **19–21% GMV share** carries structural abandonment risk — the 3-day expiry window lets impulse buyers disengage, creating artificial stockouts and frozen GMV.

### 5. Single-Item Baskets Kill Unit Economics
**~93% of orders contain exactly one product.** Fixed per-order costs can't be spread. AI cross-sell at checkout is estimated to drive **3–8% AOV uplift (+$480K–$1.3M)**.

---

## 🏆 Strategic Priority Matrix

| Priority | Recommendation | Timeline | Est. GMV Impact |
|---|---|---|---|
| 🔴 P1 | Launch Olist Prime loyalty program | 0–3 months | +$800K–$1.2M/yr |
| 🔴 P1 | Display installment pricing on all pages >$100 | 0–1 month | +$500K–$800K/yr |
| 🔴 P1 | Enforce 48-hour seller dispatch SLA | 0–2 months | ~$200K loss prevention |
| 🟡 P2 | ML-based delivery estimate tightening | 3–6 months | +$300K–$600K/yr |
| 🟡 P2 | Contract regional 3PLs for North/Northeast | 3–6 months | Retention lift in 30% of states |
| 🟡 P2 | Reduce Boleto expiry to 24h + WhatsApp reminders | 1–2 months | Inventory lock reduction |
| 🟡 P2 | AI cross-sell module at checkout | 2–4 months | +$480K–$1.3M |
| 🟢 P3 | Sunset bottom 15 product categories | 3–9 months | Ops efficiency gain |
| 🟢 P3 | Open micro-fulfilment hub in Curitiba | 6–18 months | Unlocks South market |
| 🟢 P3 | Launch B2B account management desk | 3–6 months | High-value account retention |

---

## 📁 Dataset

**Kaggle — Brazilian E-Commerce Public Dataset by Olist**  
🔗 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

~100K orders from 2016–2018 across 8 CSV files covering orders, customers, sellers, products, payments, reviews, and geolocation.

> Raw CSVs are not included due to file size. See `data/README_data.md` for instructions.

---

## 📄 License

Portfolio and educational use. Olist dataset is publicly available under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🤝 Connect

**Pruthviraj Vikas Chavan**  
Data Analyst | Strategy & Operations Advisory  
📧 chavanraj9545@gmail.com  
🔗www.linkedin.com/in/pruthvirajvikaschavan



---

*"Data without action is just noise. This report exists to turn noise into revenue."*
