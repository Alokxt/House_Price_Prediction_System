
# 🏠 **House Price Prediction**

A machine learning project to predict house prices based on various features of the house such as area, bedrooms, bathrooms, year built, and more.

---

## 🚀 **Project Overview**
- 📂 **Dataset:**  
  `House Price India.csv` containing data on:
  - Built year, living area, lot area
  - Number of bedrooms, bathrooms, floors
  - Views, renovation year, etc.

- 🎯 **Goal:**  
  Predict the **price of a house** given its features.

---

## 📊 **Data Analysis & Preprocessing**
- ✅ **Dropped irrelevant columns**:
 🔄 **Converted data types**:
  - Bathrooms & floors ➔ integers
  - 🕵️ **Checked for:**
  - Missing values
  - Duplicate rows
  - 📈 **Visuals:**
  - Heatmaps to explore feature correlations
  - Barplots of built year vs price
  
## 🤖 **Models Used**
### 🔹 **1. Ridge Regression**
- Tested multiple `alpha` values (`0.1, 1.0, 10.0, 100.0`)
- Evaluated using:
- **RMSE normalized by mean price**

### 🔹 **2. XGBoost Regressor**
- Outperformed Ridge with:
- **Higher R² score**
- **Lower normalized RMSE**
- Plotted predicted vs actual prices for visualization.

## 📈 **Results**
- 🥇 **Best performance:**  
✅ **XGBoost Regressor** with high R² and low error.

---
