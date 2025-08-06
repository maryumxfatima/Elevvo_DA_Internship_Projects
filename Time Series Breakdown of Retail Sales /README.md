# 🛒 Walmart Sales Forecasting & Trend Analysis

This project analyzes Walmart’s departmental sales data to uncover trends and forecast future sales using time series techniques.

## 📊 Project Overview

The primary goal of this project is to:
- Aggregate weekly sales data into monthly trends
- Visualize patterns and seasonality
- Apply basic forecasting, I used **Holt Winters Triple Exponential Smoothing**

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Statsmodels (ExponentialSmoothing)
- Seaborn

## 📁 Dataset
The data used is sourced from the **Walmart Weekly Sales** dataset, typically available on Kaggle. It includes fields such as:
- `Store`
- `Dept`
- `Date`
- `Weekly_Sales`
-  `IsHoliday`

## 📈 Key Steps
1. **Data Preprocessing**  
   - Parsed date field  
   - Grouped by department and month  
   - Summed weekly sales to get monthly values  

2. **Visualization**  
   - Line plots to show sales trends over time  
   - Rolling averages to smooth out short-term fluctuations  

3. **Forecasting**  
   - Applied **Holt Winters Triple Exponential Smoothing** to predict future sales  
   - Compared actual vs forecasted values  

## 📌 Project Goals
- Practice time series analysis basics  
- Learn how to apply smoothing techniques for forecasting  
- Build a simple yet insightful sales prediction model  


### 🔗 Author
**Maryam Fatima**  
For questions or collaborations, feel free to reach out!

