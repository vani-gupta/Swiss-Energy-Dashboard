# Swiss Energy Analytics Dashboard (Tableau)

This repository showcases an end-to-end data analytics project developed as part of a university coursework. The project demonstrates **data cleaning, transformation, exploratory analysis, and interactive visualization** using real-world energy data from Switzerland.

The final output is an interactive Tableau dashboard designed to support **trend analysis, policy insights, and energy market understanding**.

## 🧠 Problem Statement
How do electricity production, consumption patterns, and market prices in Switzerland evolve over time, and what insights can be derived regarding seasonality, energy mix, and external shocks (e.g., energy crises)?

## 📊 Data Sources
- Swiss Federal Office of Energy (SFOE)
- Swissgrid electricity production data
- Day-ahead electricity spot market prices (Switzerland)

## 🔧 Data Engineering & Preparation
- Restructured electricity production data by pivoting energy types into analytical features
- Cleaned and validated consumption data (null handling, duplicate removal)
- Standardized schemas and renamed fields from German to English
- Engineered derived metrics such as **Federal vs Private Electricity Consumption**

## 📈 Analytical & Visualization Components
- Time-series analysis of total electricity production and consumption (GWh)
- Price volatility analysis using day-ahead electricity prices (EUR/MWh)
- Energy mix analysis by production type (nuclear, hydro, solar, wind, thermal)
- Seasonal consumption patterns and long-term trend assessment
- Interactive filtering, drill-downs, and tooltips for exploratory analysis

## 🔍 Key Insights
- Electricity consumption exhibits strong annual seasonality driven by climate
- Energy prices remained stable until a sharp spike during the 2022 European energy crisis
- Switzerland maintains a clean energy profile dominated by renewable sources
- Photovoltaic (solar) energy production shows a clear and sustained upward trend

## 🛠️ Tools & Skills Demonstrated
- Tableau (Dashboard Design, Calculated Fields, Interactivity)
- Data Cleaning & Feature Engineering
- Time-Series Analysis
- Exploratory Data Analysis (EDA)
- Analytical Storytelling & Insight Communication

## 📁 Repository Structure
- `Swiss_Energy_Dashboard.twbx` – Tableau packaged workbook  
- `Documentation of Dashboard.pdf` – Detailed methodology, visual explanations, and insights

## ▶️ How to View
1. Download the `.twbx` file
2. Open using **Tableau Desktop** or **Tableau Reader**

## 📌 Context
This project was completed as part of a university program and is intended to demonstrate practical data analytics skills on real-world, policy-relevant datasets.

