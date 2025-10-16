# 🛒 Maven Market Power BI Dashboard

An end-to-end **Power BI project** analyzing sales and performance data for Maven Market — focusing on revenue trends, profit margins, transactions, and regional performance across North America (USA, Canada, Mexico).

![Dashboard Preview](https://github.com/Harshits9/Maven-Market-Dashboard/blob/main/MavenProject.png)

---

## 📊 Project Overview

This dashboard provides actionable insights into Maven Market’s sales performance, allowing stakeholders to monitor KPIs, track goals, and identify growth opportunities.

### Key Objectives:
- Visualize total **revenue, profit margin, and return rate**
- Track **weekly revenue trends** and **regional performance**
- Compare **actual vs target** metrics for transactions and profit
- Highlight **top-performing brands** and underperforming areas

---

## ⚙️ Tools & Technologies
- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX (Data Analysis Expressions)** for measure creation
- **Excel / CSV datasets** for data input

---

## 📈 Major KPIs & Metrics
| Metric | Description |
|--------|--------------|
| **Total Revenue** | Overall sales revenue generated |
| **Total Transactions** | Count of transactions processed |
| **Profit Margin (%)** | Profitability across brands |
| **Return Rate (%)** | Returned orders proportion |
| **Goal Tracking** | Comparison of actuals vs targets |

---

## 🌎 Insights Discovered
- **Portland** achieved 1,000+ sales, marking a key regional milestone.  
- **Average profit margin:** ~59% across all brands.  
- **Return rates** remained low (1.5%), showing healthy operations.  
- **Revenue Goal Achievement:** 6.4% above the monthly target.  

---

## 🧠 DAX Measures Used
A few sample measures implemented in Power BI:
```DAX
Total Revenue = SUM('Sales'[Revenue])
Total Profit = SUM('Sales'[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Revenue], 0)
Return Rate % = DIVIDE([Returned Items], [Total Transactions], 0)
Revenue Goal % = DIVIDE([Total Revenue], [Target Revenue], 0)
