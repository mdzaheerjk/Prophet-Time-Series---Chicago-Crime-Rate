# 🕵️‍♂️ Chicago Crime Rate Prediction using Facebook Prophet

This project uses **Facebook Prophet**, a time series forecasting model, to analyze and predict **crime trends in Chicago** from 2001 to 2017.

> 📌 Project 3 - Time Series Forecasting  
> 📁 Repository: [`Prophet-Time-Series---Chicago-Crime-Rate`](https://github.com/mdzaheerjk/Prophet-Time-Series---Chicago-Crime-Rate)

---

## 🔍 Problem Statement

The goal is to predict future crime occurrences in Chicago based on historical data using Facebook Prophet. The objective is to identify seasonal patterns and long-term trends that can assist in better planning for public safety and crime prevention.

---

## 📊 Dataset

| File Name                        | Description                           |
|----------------------------------|---------------------------------------|
| `Chicago_Crimes_2001_to_2004.csv` | Crime data from 2001–2004             |
| `Chicago_Crimes_2005_to_2007.csv` | Crime data from 2005–2007             |
| `Chicago_Crimes_2008_to_2011.csv` | Crime data from 2008–2011             |
| `Chicago_Crimes_2012_to_2017.csv` | Crime data from 2012–2017             |

- **Source:** [Chicago Data Portal](https://data.cityofchicago.org/)
- **Type:** Daily crime records
- **Preprocessing:** Combined, cleaned, and aggregated to monthly frequency for Prophet forecasting.

---

## 🔧 Tools & Technologies

- 🐍 Python
- 🧠 [Facebook Prophet](https://facebook.github.io/prophet/)
- 📊 Pandas, Matplotlib, Plotly
- 📁 Jupyter Notebook

---

## 🧠 Forecasting Workflow

- 🔹 Load and combine multiple CSV files
- 🔹 Convert datetime format and group by month
- 🔹 Apply Prophet forecasting
- 🔹 Visualize trends, seasonality, and predictions
- 🔹 Evaluate performance (visually & statistically)

---

## 🛠️ Installation & Execution

### ✅ Step 1: Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Prophet-Time-Series---Chicago-Crime-Rate.git
cd Prophet-Time-Series---Chicago-Crime-Rate

