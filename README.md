[README (2).md](https://github.com/user-attachments/files/29658443/README.2.md)
# 💹 FinSight — Finance Analytics Dashboard

An interactive **Power BI** dashboard built to help a financial organization monitor and analyze transactions, customer behavior, fees, taxes, and performance across business segments and regions — in real time.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

---

## 📖 Overview

Management teams in financial organizations often struggle to get a unified view of transaction health, customer contribution, and regional performance. **FinSight** solves this by consolidating all key financial metrics into a single, interactive Power BI report with two dedicated views:

- **Overview Analysis** – executive-level KPIs and visual trends
- **Transactions** – a detailed, filterable grid for drilling into individual records

The dashboard is **fully dynamic** — every KPI and chart responds instantly to the selected **Year**, **Dynamic Metric**, **Occupation**, and **Category** filters, so stakeholders can slice the data however they need without touching the underlying model. This enables real-time KPI tracking, identification of high-performing customer segments and states, transaction pattern analysis, fees/tax monitoring, and ultimately faster, better-informed financial decisions.

---

## 🖼️ Dashboard Preview

### Overview Analysis
> KPI summary cards, monthly trend, transaction status breakdown, customer segment, state-wise, transaction type, and gender-wise analysis.

![Overview Analysis](assets/Overview_Analysis.png)

### Transactions
> Detailed, filterable transaction-level grid for granular drill-down.

![Transactions](assets/Transactions.png)

> 📌 *Add the dashboard screenshots to an `assets/` folder in the repo so they render in this README.*

---

## 🎯 Business Objective

A financial organization needed a centralized analytical solution to help stakeholders:

- Monitor KPIs in real time
- Identify high-performing customer segments and states
- Analyze transaction patterns and trends
- Track operational fees and taxes
- Understand customer demographics
- Improve financial decision-making and business strategy

Full requirements are documented in [`docs/Business Requirements.pdf`](docs/Bussiness%20Requrements.pdf).

---

## 📊 Key Features

### Main KPIs
| KPI | Description |
|---|---|
| **Total Amount** | Total transaction amount processed, with YoY growth comparison |
| **Total Transactions** | Total number of transactions with yearly volume tracking |
| **Avg. Transaction Value** | Average amount per transaction |
| **Total Fees** | Total fees collected across all transactions |
| **Total Tax** | Total tax generated across all transactions |

### Visualizations
| Chart | Type | Purpose |
|---|---|---|
| Total Amount by Month | Line / Area Chart | Spot monthly trends, seasonal spikes and dips |
| Total Amount by Transaction Status | Donut Chart | Compare Success / Failed / Pending volumes to gauge operational efficiency |
| Total Amount by Customer Segment | Horizontal Bar | Rank segment contribution (Retail, Premium, SME, Corporate, Wealth) |
| Total Amount by State | Horizontal Bar | Identify top-performing states/regions |
| Transaction Type Analysis | Matrix / Heatmap Table | Amount, Fees, Tax & Count by transaction type (Bill Payment, Loan EMI, Transfer, etc.) |
| Total Amount by Gender | Donut Chart | Customer demographic participation |

### Interactive Filters
- **Year**
- **Dynamic Metric** (switch the measure driving the visuals)
- **Occupation**
- **Category**

All charts and KPI cards update live based on the combination of filters selected — no page refresh or manual recalculation needed.

---

## 🗂️ Repository Structure

```
Finance-Analysis/
│
├── datasets/
│   ├── customers.csv               # Customer master data
│   └── finance_transactions.csv    # Core transactions dataset
│
├── docs/
│   └── Bussiness Requrements.pdf   # Project business requirements
│
├── finance_analysis.pbix/
│   └── Finance Analysis Project.pbix   # Power BI report file
│
├── LICENSE
└── README.md
```

---

## 🛠️ Tech Stack

- **Power BI Desktop** – data modeling, DAX measures, and visualization
- **DAX** – KPI calculations, YoY growth, dynamic measures
- **Power Query (M)** – data cleaning and transformation
- **CSV** – source datasets (customers & transactions)

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Duddukuri-Avinash/Finance-Analysis.git
   ```
2. Open `finance_analysis.pbix/Finance Analysis Project.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to point to the `datasets/` folder on your machine.
4. Refresh the data and explore the **Overview Analysis** and **Transactions** pages.

> Requires [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to open and edit the `.pbix` file. A [Power BI Report Server / Service](https://app.powerbi.com/) account is only needed if you want to publish it online.

---

## 📌 Key Insights

- Total transaction volume reached **₹732.18K** across **64 transactions**, up **29.65% YoY**.
- **Retail** customers are the largest contributing segment, followed by **Premium**.
- **Karnataka** leads state-wise transaction value, followed by Gujarat and Maharashtra.
- **Loan EMI** and **Transfer** are the highest-value transaction types.
- Transaction success rate remains high, with a comparatively small share of failed/pending transactions.

*(Figures reflect the sample dataset used for this project and will update dynamically as new data is loaded.)*

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Duddukuri Avinash**
🔗 [GitHub](https://github.com/Duddukuri-Avinash)

If you find this project useful, consider giving it a ⭐ on GitHub!
