# 🛍️ Customer Segmentation using RFM Analysis

This project applies **RFM (Recency, Frequency, Monetary) analysis** to the **Online Retail Dataset** (UCI Machine Learning Repository) to segment customers based on their purchase behaviour.  
The goal is to identify key customer groups and suggest actionable marketing strategies.

## 📂 Project Overview

1. **Data Cleaning**
   - Removed missing `CustomerID` (cannot track customers without IDs)
   - Removed cancelled transactions and negative/zero quantities or prices
   - Removed missing product descriptions
   - Created `TotalSum` column for transaction-level spend

2. **RFM Calculation**
   - **Recency:** Days since last purchase  
   - **Frequency:** Number of unique purchase transactions  
   - **Monetary:** Total amount spent  

3. **RFM Scoring & Segmentation**
   - Customers scored 1–4 for each R, F, and M metric using quartiles  
   - Combined scores into `RFM_Score` and grouped customers into segments:
     - **Champions**
     - **Loyal Customers**
     - **Potential Loyalists**
     - **At Risk**

4. **Visualisation**
   - Bar chart of customer segments  
   - Heatmap of average monetary value by Recency & Frequency scores  

5. **Marketing Insights**
   - Developed data-driven strategies for each segment to boost retention, reactivation, and revenue growth.

---

## 📊 Dataset

- **Name:** Online Retail Dataset (UCI)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Data includes transactions for a UK-based online retailer from 2010–2011.

---

## 🔧 Tools & Libraries

- **Python**  
- **Pandas** – data cleaning & RFM calculation  
- **Matplotlib & Seaborn** – visualisation  

---

