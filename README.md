# skycity-auckland-channel-analytics
# 🍽️ SkyCity Auckland — Order Channel Analytics

An advanced data analytics project analyzing order channel performance and market share across SkyCity Auckland's restaurant and bar network.

---
<img width="1742" height="719" alt="Screenshot 2026-03-18 121218" src="https://github.com/user-attachments/assets/d2e4e987-e2cc-460e-8373-a8aa15afe99b" />
<img width="1751" height="701" alt="Screenshot 2026-03-18 121148" src="https://github.com/user-attachments/assets/f1002fc1-7070-4d6f-9fd6-f589835cab8b" />
<img width="1783" height="701" alt="Screenshot 2026-03-18 121120" src="https://github.com/user-attachments/assets/98b57f17-0f38-4e41-b092-8089614ba719" />

## 📋 Project Overview

| | |
|---|---|
| **Domain** | Data Analyst |
| **Level** | Advanced |
| **Tools** | Python, Pandas, Matplotlib, Seaborn, Chart.js |
| **Dataset** | SkyCity_Auckland_Restaurants___Bars.csv |
| **Restaurants** | 1,696 |
| **Channels** | I

n-Store · Uber Eats · DoorDash · Self-Delivery |
| **Subregions** | CBD · North Shore · South Auckland · West Auckland |

---

## 📁 Project Structure
```
skycity-auckland-channel-analytics/
│
├── SkyCity_Auckland_Channel_Analysis.ipynb   # Main notebook
├── SkyCity_Auckland_Restaurants___Bars.csv   # Dataset
└── README.md
```

---

## 📊 Dataset Columns

| Column | Description |
|---|---|
| `RestaurantID` | Unique restaurant identifier |
| `CuisineType` | Food category (Burgers, Pizza, Indian etc.) |
| `Segment` | Business type (Cafe, QSR, Ghost Kitchen, Full-service) |
| `Subregion` | Geographic area within Auckland |
| `MonthlyOrders` | Total orders across all channels |
| `InStoreOrders` | Walk-in orders count |
| `UberEatsOrders` | Orders via Uber Eats |
| `DoorDashOrders` | Orders via DoorDash |
| `SelfDeliveryOrders` | Orders via restaurant's own delivery |
| `InStoreNetProfit` | Net profit from in-store channel |
| `UberEatsNetProfit` | Net profit from Uber Eats |
| `DoorDashNetProfit` | Net profit from DoorDash |
| `SelfDeliveryNetProfit` | Net profit from self-delivery |

---

## 🔍 Project Steps

1. **Data Validation** — null checks, order count consistency, share sum verification
2. **KPI Summary** — total orders, revenue, profit, risk count
3. **Channel Market Share** — order volume, revenue and profit margin by channel
4. **Geographic Analysis** — channel mix across 4 Auckland subregions
5. **Cuisine Analysis** — channel preferences by food category
6. **Segment Analysis** — channel mix by business type
7. **Dependency Risk** — flags restaurants with >70% aggregator reliance
8. **Profitability Analysis** — margin % and revenue vs profit comparison
9. **Interactive Dashboard** — Chart.js dashboard embedded in Colab

---

## 💡 Key Findings

- 📦 Uber Eats dominates with **39.6%** of all orders but only **0.84%** profit margin
- 💰 In-Store has the highest margin at **26.8%** — most profitable channel
- ⚠️ **65% of restaurants** (1,102) are high-risk with >70% aggregator dependency
- 🗺️ North Shore has the highest risk rate at **67.4%**
- 👻 Ghost Kitchen segment most vulnerable — only **6.2%** in-store orders
- 🚗 Self-Delivery underutilised despite **22.9%** margin and zero commission

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `SkyCity_Auckland_Channel_Analysis.ipynb`
3. Run Cell 1 — imports all libraries
4. Run Cell 2 — upload the CSV when prompted
5. Run all remaining cells top to bottom
6. Last cell renders the interactive dashboard

---

## 📦 Dependencies
```
pandas
numpy
matplotlib
seaborn
```

Install:
```bash
pip install pandas numpy matplotlib seaborn
```

---

## 📌 Recommendations

1. Invest in Self-Delivery — 22.9% margin with no commission fees
2. Build in-store loyalty programs to reduce aggregator reliance
3. Ghost Kitchens should develop direct ordering channels urgently
4. North Shore restaurants need immediate channel diversification
5. Japanese and Kebab cuisines show highest Uber Eats dependency (48%)

---

## 👤 Author

Made as part of the **Unified Mentor** Data Analyst internship project series.
