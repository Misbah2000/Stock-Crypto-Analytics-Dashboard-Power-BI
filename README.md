# **Stock & Crypto Analytics Dashboard – Power BI**

A visually rich and interactive Power BI dashboard designed to analyze **Stock Market** and **Cryptocurrency** trends with real-time insights, historical comparisons, and actionable metrics.

---

## 🚀 **Project Overview**

This project showcases a complete end‑to‑end analysis of stock and cryptocurrency performance using Power BI. It includes:

* Trend analysis
* Daily/weekly price movement tracking
* Market comparison
* Top gainers & losers
* Volume analysis
* Interactive filters

The goal of this dashboard is to help users understand market movements quickly and make data-driven decisions.

---

## 📊 **Key Features**

* 📈 **Dynamic Line Charts** for price trends
* 💹 **Candlestick charts** for detailed price visualization
* 📉 **Top Gainers & Losers** cards
* 🔍 **Search & Filter by stock/crypto symbol**
* 🧮 **KPIs** — Open, Close, High, Low, Volume
* 🗂️ **Historical vs Current performance comparison**
* 🧭 **User-friendly navigation** with buttons

---

## 🛠️ **Tools & Technologies Used**

* **Power BI Desktop** (Main tool)
* * **Power BI Service**
* **Power Query** (ETL)
* **DAX** (Measures & Calculations)
* **CSV/Excel datasets** for stocks & crypto

---

## 📁 **Project Structure**

```
📦 Stock-Crypto-PowerBI-Dashboard
 ┣ 📄 PowerBi_Stock&Cripto_Project.pbix
 ┣ 📁 Dataset/
 ┃ ┣ stocks.csv
 ┃ ┣ crypto.csv
 ┗ 📄 README.md
```

---

## 🧮 **Important DAX Measures**

Some sample DAX calculations used:

```DAX
Daily Change % = DIVIDE([Close] - [Open], [Open])

7 Day Average = AVERAGEX(LASTN(7, 'Market Data'), [Close])
```

---

## 🔧 **How to Use This Project**

1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. Load or update datasets in the *Dataset* folder if needed.
4. Explore the dashboard using filters and navigation buttons.

---

## 🌟 **Why This Project?**

This dashboard is ideal for:

* Investors & traders
* Students and data analysts
* Anyone learning Power BI
* Portfolio analytics & market study

---

## 🤝 **Contributing**

Pull requests are welcome! If you want to enhance visualizations or add datasets, feel free to contribute.

---

### ⭐ If you like this project, consider giving the repository a star!

# 🔴 Live Power BI Report (Interactive) #

👉 Click to open the full interactive dashboard:
## ➡️ Live Power BI Report 📊💰 ##

📌 Opens in your browser — best viewed on desktop for full experience.*
