# 📊 Sales Forecasting & Demand Analysis

## 📌 Overview
This project focuses on forecasting product demand using historical sales data and machine learning techniques. The goal is to support data-driven decision-making and improve operational planning.

## 🎯 Business Problem
Accurate demand forecasting is essential for inventory management and strategic planning. In this case, the forecasting process was performed manually, which can lead to inconsistencies and inefficiencies.

## ⚙️ Approach
- Data cleaning and preprocessing  
- Time series aggregation (monthly level)  
- Feature engineering using lag variables  
- Model training using machine learning (Random Forest)  
- Model evaluation using MAE  
- Scenario analysis with and without outliers  

## 🤖 Model
- Random Forest Regressor  
- Input features: lag1, lag2, lag3 (previous months demand)  

## 📈 Results
- Baseline model MAE: 142  
- Improved model MAE (excluding outliers): 88  
- ~38% improvement in prediction accuracy  
![Forecast vs Real](images/forecast_vs_real.png)
## 💡 Key Insights
- Demand follows a relatively stable pattern under normal conditions  
- High variability is driven by extraordinary events (e.g., large customers)  
- These events significantly affect model performance  

## 🚀 Business Impact
The model enables:
- Better demand estimation  
- Improved inventory planning  
- Reduction of manual forecasting processes  

## 🔍 Key Finding
Demand can be segmented into:
- Regular demand (predictable)  
- Extraordinary demand (event-driven)  

## 🔮 Next Steps
- Incorporate additional features (customer behavior, external factors)  
- Segment models for regular vs. extraordinary demand  
- Improve model tuning and evaluation  
- Automate the forecasting pipeline  
- Monitor model performance over time  

## ⚠️ Note
The dataset used in this project is not included due to confidentiality reasons.

## 🛠️ Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib
