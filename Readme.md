# 🛒 Retail Demand Forecasting & Inventory Optimization — Walmart Case Study

> **By Thobeka Jali – Data Scientist**

Refer to project site [https://retail-forecasting-viz.lovable.app]

---

## 🚀 Project Overview

In today's dynamic retail landscape, **efficient inventory management** and **accurate demand forecasting** are critical to profitability and customer satisfaction. This project presents an **AI-powered forecasting and inventory optimization solution** built for a 45-store retail chain — modeled on Walmart's operations.

Using a **hybrid model approach (SARIMAX + LSTM)**, this solution integrates time-series trends, nonlinear relationships, and real-world market drivers (fuel prices, temperature, holidays) to deliver **actionable insights** through Power BI dashboards.

---

## 🔍 Key Business Challenges Addressed

- 🎯 Unpredictable customer demand during holidays and promotions  
- 🏬 Inventory imbalances across stores (overstocking vs understocking)  
- 🌍 Inconsistent performance across locations and time  
- 📉 Missed sales, excess holding costs, and customer dissatisfaction  

---

## 🧠 Forecasting Solution Highlights

### 📊 Hybrid AI Models
- **SARIMAX**: Captures short-term, seasonal patterns with interpretable outputs  
- **LSTM**: Detects long-term nonlinear demand shifts due to promotions, weather, and events  

### 🌐 Input Data Sources
- Historical sales data across 3 years  
- Calendar effects (holidays, promotions)  
- Macroeconomic factors (fuel prices, temperature)  

### 🖥️ Visualization & Dashboards
- Built with **Power BI**  
- Dashboard 1: Executive KPIs
- ![KPI Dashboard](images/Dashboard_1.png)
- Dashboard 2: Store-level performance insights
- ![Store Level Performance](images/dashboard_2.png)

---

## 📈 Forecasting Use Cases

| Time Horizon | Forecast Output | Business Impact |
|--------------|------------------|------------------|
| Weekly       | 156-step rolling forecast | Real-time pricing, staffing, restocking |
| Monthly      | 36-step forecast | Seasonal inventory optimization |
| Quarterly    | 12-step forecast | Strategic planning, vendor management |

---

## 🧩 Inventory Optimization Strategy

- Dynamic reorder point automation with safety stock buffers  
- Supplier procurement aligned with rolling forecasts  
- Store-level inventory personalization based on demand clusters  
- Seasonal SKU bundling + price elasticity-informed stocking  
- Operational KPI monitoring (stockouts, overstock %, sell-through, forecast accuracy)

---

## ✅ Results & Strategic Value

- 📉 Reduced stockouts & inventory holding costs  
- 📈 Increased full-price sales and gross margin  
- 💡 Localized decision-making and promotion planning  
- 📊 Embedded forecasting into strategic and operational workflows  

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**: `statsmodels`, `tensorflow/keras`, `pandas`, `numpy`  
- **Tools**: Power BI, Excel  
- **Models**: SARIMAX, LSTM  
- **Evaluation Metrics**: RMSE, MAE, MAPE, Backtesting  

---

## 📌 Project Structure
````
📁 /retail-forecasting-walmart
├── data/ # Cleaned and enriched datasets
├── notebooks/ # Jupyter notebooks for modeling and EDA
├── reports/ # Visuals and dashboards
├── models/ # Trained SARIMAX and LSTM models
├── README.md # This file
└── requirements.txt # Python dependencies
````

---

## 📚 What You'll Learn

- How to blend **classical statistical models** with **deep learning** for robust retail forecasting  
- How to integrate external factors (temperature, fuel price) for more accurate predictions  
- How to build a data-driven **inventory and replenishment** system  
- How to design and deliver **executive-level insights** using Power BI  

---

## 📄 Full Case Study

For detailed methodology, insights, dashboards, and forecasting visualizations:  
➡️ [Download the Full Report (PDF)](./Demand%20Forecasting%20Report.pdf)

---

## 💼 About the Author

**Thobeka Jali**  
Data Scientist | Retail Analytics | Predictive Modeling  
Connect on [Email](thobekaj63@gmail.com)  
Portfolio: [thobekanelisiwejali.github.io](https://yourname.github.io)

---

## 🤝 Let's Collaborate

Interested in AI for retail, time-series forecasting, or business optimization?  
Let’s collaborate or connect!

---
