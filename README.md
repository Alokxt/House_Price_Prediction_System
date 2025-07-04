# House_Price_Prediction_System
🏠 House Price Prediction
This project builds a regression system to predict house prices based on various features of the house, such as number of bedrooms, bathrooms, area, built year, etc.

🚀 Overview
Dataset:
A house pricing dataset (House Price India.csv) containing details about houses such as:

Built year, living area, lot area , Number of bedrooms, bathrooms, floors , Renovation year, views And more.

Goal:
Predict the price of a house given its features.

📊 Data Analysis & Preprocessing
Dropped irrelevant columns like postal codes, latitude/longitude, Date.

Converted dtypes of columns (number of bathrooms, floors) to integers.

Checked for and handled:

Missing values

Duplicates

Explored correlations via heatmaps.

Visualized prices with respect to built year.

🧠 Models Used
Ridge Regression

Tried different alpha values (0.1, 1.0, 10.0, 100.0).

Evaluated using RMSE normalized by mean house price.

XGBoost Regressor

Achieved better fit with lower RMSE and higher R² score.

Plotted predicted vs actual prices to visualize performance.


📈 Results
XGBoost Regressor achieved:

High R² score indicating a strong fit.

RMSE normalized by mean price significantly lower than Ridge.

