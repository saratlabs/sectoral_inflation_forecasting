# 📈 Sectoral Inflation Forecasting using Econometrics & Time Series Modeling

---

## 🚀 Project Objective

This project aims to **forecast sector-wise inflation rates across multiple countries** using a simulated macroeconomic dataset. The analysis supports policymakers and economists in identifying **volatile sectors**, implementing **targeted interventions**, and framing **sector-sensitive inflation policies**.

---

## 🧠 Background

Inflation is not monolithic—it varies across sectors due to factors like supply chains, regulations, and external shocks. A deeper analysis at the **sectoral level** provides insights beyond country-level aggregates. This project focuses on modeling inflation at the sector level and deriving actionable **policy recommendations**.

---

## 🗃️ Dataset

As real-world sectoral inflation data is sparse and fragmented, we used **synthetically generated data** representing:

* 📅 **Years**: 2010 to 2024
* 🌍 **Countries**: USA, Germany, India, Brazil, France
* 🏭 **Sectors**: Energy, Food, Transport, Manufacturing, Technology, Healthcare, Education
* 📊 **Target**: Forecasted Inflation Rate (%)

All features are clean, formatted, and structured for time series econometric modeling.

---

## 🔧 Methodology

### ✅ Notebook 01: Data Exploration & Cleaning

* Handled missing values and reshaped the dataset for time series compatibility
* Performed summary statistics and trend exploration

### 📉 Notebook 02: Time Series Modeling

* Grouped data by `Country` and `Sector`
* Applied **ARIMA (AutoRegressive Integrated Moving Average)** models
* Generated **forecasts for each sector-country pair**

### 📈 Notebook 03: Forecast Visualization

* Line plots of historical vs forecasted inflation
* Plots grouped by country and sector for interpretability

### 📊 Notebook 04: Model Evaluation

* Metrics:

  * **RMSE** (Root Mean Squared Error) for accuracy
  * **R² Score** for model fit
* Model performed well across most sectors with R² > 0.75

### 🧩 Notebook 05: Policy Implication Analysis

* Identified high and low volatility sectors
* Aggregated mean forecasts and volatility using `groupby`
* Provided **policy takeaways for inflation stabilization and targeting**

---

## 📌 Key Findings

| Sector     | Policy Insight                                            |
| ---------- | --------------------------------------------------------- |
| Energy     | High volatility — needs price buffering/subsidy schemes   |
| Food       | Susceptible to shocks — recommend strategic food reserves |
| Transport  | Affected by oil prices — suggest fuel tax reforms         |
| Technology | Stable — ideal for long-term investment and FDI           |
| Healthcare | Low volatility — focus on expansion and public access     |

---

## 🧠 Policy Recommendations

* **Targeted Sectoral Inflation Policies**: Avoid one-size-fits-all inflation controls
* **Buffer Mechanisms**: Use subsidies and tax relief in volatile sectors
* **Sector-Sensitive Interest Rates**: Guide monetary policy based on volatility mapping
* **Data-Driven Fiscal Planning**: Allocate resources using forecast-backed insights

---

## 📂 Folder Structure

```bash
sectoral_inflation_forecasting/
│
├── 01_data_exploration.ipynb
├── 02_arima_modeling.ipynb
├── 03_forecast_visualization.ipynb
├── 04_model_evaluation.ipynb
├── 05_policy_implication_analysis.ipynb
├── data/
│   └── synthetic_sectoral_inflation.csv
└── README.md
```

---

## 🤝 Contribution & Credits

* 👨‍💻 Project Lead: Sai Sarat Chandra
* 🧠 Concept: Econometric modeling for inflation volatility
* 💻 Tools: Python, pandas, statsmodels, matplotlib, seaborn

---
