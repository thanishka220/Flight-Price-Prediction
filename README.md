# Flight Price Prediction 🚀

## Overview
This project predicts flight ticket prices using **10 different machine learning models**.  
It processes flight-related data such as departure times, airline types, and travel duration to find the best predictive model.

### Model Comparison – Evaluate models using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## Data Preprocessing:
- Handle missing values  
- Extract date, time, and duration features  
- Encode categorical variables  
- Scale numerical features  

## Models Used:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  
- K-Nearest Neighbors (KNN) Regressor  
- XGBoost Regressor  
- Lasso Regression  
- Ridge Regression  
- Multi-Layer Perceptron (MLP) Regressor  

## Dataset
The dataset contains flight details including:
- Total Stops  
- Departure & Arrival Time  
- Journey Date Features (Day, Month)  
- Airlines & Source-Destination  
- Duration & Additional Info  
- Price (Target Variable in training set)  

## Conclusion
After evaluating multiple machine learning models, **XGBoost Regressor** emerged as the best performer for flight price prediction. It achieved:

- **Lowest Mean Squared Error (MSE):** 2,487,425.75  
- **Highest R² Score:** 0.88  

**Random Forest Regressor** also delivered solid performance with an **R² score of 0.86**.  
On the other hand, **Support Vector Regressor (SVR)** had the weakest performance, with an **R² score of 0.035**.

## Key Takeaway
For **high accuracy and efficiency**, **XGBoost Regressor** is the best model, but **Random Forest Regressor** remains a strong competitor.  
Future improvements could explore **hyperparameter tuning** or additional **feature engineering**.

