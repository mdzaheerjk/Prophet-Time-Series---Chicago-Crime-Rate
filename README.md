# 🚨 Chicago Crime Rate Analysis & Prediction (2001–2017)

![Crime Analysis](https://img.shields.io/badge/Analytics-Crime_Data-blue) 
![Python](https://img.shields.io/badge/Python-3.8%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)

A comprehensive **data analysis + machine learning** project that predicts crime trends in Chicago using historical data. Designed to support law enforcement and urban planning through data-driven insights.

> 📌 **Course Project** - Data Analysis & Machine Learning  
> 📁 **Repository**: `project2-Chicago-Crime-Rate`

---

## 📌 Project Highlights

- 🔍 **17 years** of crime data analyzed (2001-2017)
- 📊 **Interactive visualizations** of crime patterns
- 🔮 **Predictive modeling** for future crime trends
- 📍 **Geospatial analysis** of crime hotspots
- ⚡ **Optimized** machine learning pipelines

---

## 📂 Dataset Overview

**Source:** [Chicago Data Portal](https://data.cityofchicago.org/)

| File | Records | Time Period | Size |
|------|---------|-------------|------|
| `Chicago_Crimes_2001_to_2004.csv` | ~1.2M | 2001-2004 | 450MB |
| `Chicago_Crimes_2005_to_2007.csv` | ~1.1M | 2005-2007 | 420MB |
| `Chicago_Crimes_2008_to_2011.csv` | ~1.4M | 2008-2011 | 520MB |
| `Chicago_Crimes_2012_to_2017.csv` | ~1.5M | 2012-2017 | 580MB |

---

## 🔧 Technical Stack

### 📊 Data Processing
![Pandas](https://img.shields.io/badge/Pandas-1.3+-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-brightgreen)

### 📈 Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-lightblue)
![Plotly](https://img.shields.io/badge/Plotly-5.8+-blueviolet)

### 🗺️ Geospatial
![Geopandas](https://img.shields.io/badge/GeoPandas-0.10+-green)
![Folium](https://img.shields.io/badge/Folium-0.12+-darkgreen)

### 🤖 Machine Learning
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-red)
![XGBoost](https://img.shields.io/badge/XGBoost-1.6+-green)

---

## 🚀 Implementation Workflow

```mermaid
graph TD
    A[Raw Data] --> B[Data Cleaning]
    B --> C[Feature Engineering]
    C --> D[Exploratory Analysis]
    D --> E[Model Training]
    E --> F[Evaluation]
    F --> G[Visualization]
