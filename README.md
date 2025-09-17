# Team D: HireCast – Seasonal Hiring Trends & Forecast  
**DATA 606 Capstone Project (Fall 2025)**  
**Team D – Rithesh Donthoju, Kishan Haravu Pradeep, Vineeth Jutur**

---

## 📌 Project Overview
HireCast explores seasonal hiring patterns in the U.S. labor market using JOLTS Hires data from BLS/FRED and enriched macroeconomic indicators.  
Our goal is to build a predictive model that identifies peak hiring months and forecasts trends for the next 12 months.

---

## 📂 Repository Structure
- **data/** – raw and processed datasets (links for large files).  
- **notebooks/** – Jupyter notebooks for EDA, feature engineering, and modeling.  
- **src/** – Python scripts for preprocessing and helper functions.  
- **results/** – figures, tables, baseline metrics, forecast outputs.  
- **docs/** – presentations (P1, P2, P3) and final report.  

---

## 📊 Dataset Sources
- JOLTS – Hires (BLS/FRED): https://fred.stlouisfed.org/series/JTSHIL  
- Job Openings: https://fred.stlouisfed.org/series/JTSJOL  
- Unemployment Rate: https://fred.stlouisfed.org/series/UNRATE  
- Initial Claims: https://fred.stlouisfed.org/series/ICSA  
- Indeed Hiring Lab – Job Postings Index: https://fred.stlouisfed.org/series/IHLIDXUS  

---

## 🚀 Methods
- **Baseline:** Seasonal-Naïve forecast.  
- **Planned Models:** SARIMAX with exogenous variables, Gradient Boosting.  
- **Evaluation Metrics:** MAE, RMSE, MAPE, MASE, Directional Accuracy.  

---

## 📌 Deliverables
- Phase 1 (P1): Dataset prep, baseline, and EDA.  
- Phase 2 (P2): Model training & evaluation.  
- Phase 3 (P3): Forecasts, interpretation, final report.  

---

## 🔗 Team GitHub Page
This repository will host all code, results, and documentation for HireCast.
