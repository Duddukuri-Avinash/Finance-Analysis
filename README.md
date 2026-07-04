# 📊 FinSight — Finance Analytics Dashboard

An interactive Power BI dashboard to monitor and analyze financial transactions, customer behavior, fees, taxes, and performance across business segments and regions.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoftexcel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)

---

## 📖 About

FinSight is a two-page Power BI report built for a financial organization to track KPIs, customer segments, regional performance, and transaction trends — all in one place.

⚡ **Fully dynamic** — every chart and KPI updates instantly based on the **Year**, **Dynamic Metric**, **Occupation**, and **Category** filters, so users can slice the data any way they need.

---

## 🖥️ Dashboard Preview

### 🧭 Overview Analysis
![Overview Analysis](assets/Overview_Analysis.png)

### 📋 Transactions
![Transactions](assets/Transactions.png)

> 🗂️ Add screenshots to an `assets/` folder for them to display here.

---

## 🎯 Objective

Give stakeholders a centralized view to:

- 📈 Monitor KPIs in real time
- 🏆 Identify high-performing customer segments and states
- 🔍 Analyze transaction patterns and trends
- 💰 Track operational fees and taxes
- 👥 Understand customer demographics

📄 Full requirements: [`docs/Bussiness Requrements.pdf`](docs/Bussiness%20Requrements.pdf)

---

## 📌 Key Metrics (KPIs)

| Icon | KPI | Description |
|:---:|---|---|
| 💵 | Total Amount | Total transaction amount, with YoY growth |
| 🔢 | Total Transactions | Total transaction count, tracked yearly |
| ⚖️ | Avg. Transaction Value | Average amount per transaction |
| 🧾 | Total Fees | Total fees collected |
| 🏛️ | Total Tax | Total tax generated |

---

## 📊 Visuals

| Icon | Chart | Type |
|:---:|---|---|
| 📅 | Total Amount by Month | Line / Area Chart |
| ✅ | Total Amount by Transaction Status | Donut Chart |
| 🧑‍🤝‍🧑 | Total Amount by Customer Segment | Horizontal Bar |
| 🗺️ | Total Amount by State | Horizontal Bar |
| 🔁 | Transaction Type Analysis | Matrix / Heatmap |
| ⚧ | Total Amount by Gender | Donut Chart |

---

## 🎛️ Filters

🗓️ Year &nbsp;|&nbsp; 🔄 Dynamic Metric &nbsp;|&nbsp; 💼 Occupation &nbsp;|&nbsp; 🏷️ Category

---

## 🗂️ Repository Structure

```
Finance-Analysis/
│
├── 📁 datasets/
│   ├── customers.csv
│   └── finance_transactions.csv
│
├── 📁 docs/
│   └── Bussiness Requrements.pdf
│
├── 📁 finance_analysis.pbix/
│   └── Finance Analysis Project.pbix
│
├── 📄 LICENSE
└── 📄 README.md
```

---

## 🛠️ Tech Stack

🔷 Power BI Desktop &nbsp;|&nbsp; 🧮 DAX &nbsp;|&nbsp; 🔧 Power Query (M) &nbsp;|&nbsp; 📑 CSV

---

## 🚀 How to Use

1. Clone the repo
2. Open `Finance Analysis Project.pbix` in Power BI Desktop
3. Point the data source to the `datasets/` folder
4. Refresh & explore 🎉

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Duddukuri Avinash** — [GitHub](https://github.com/Duddukuri-Avinash)

⭐ If you found this useful, consider starring the repo!
