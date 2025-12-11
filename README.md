# House Price Prediction ML Project

## Objective
Predict house prices using Python, Pandas, and Machine Learning models with clean preprocessing and visualizations.

## Dataset
- The project uses the *Kaggle House Prices: Advanced Regression Techniques* dataset.
- Link: [Kaggle Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## Features
- Handles missing values using median (numeric) and 'None' (categorical).
- Categorical features encoded using One-Hot Encoding.
- Models used: Linear Regression and Random Forest Regressor.
- Train-test split: 80% train, 20% test.

## Visualizations
- *Correlation Heatmap* – shows relationship between numeric features.
- *Top 5 Important Features* – shows which features most affect house price.
- *Distribution of Prediction Errors* – evaluates model performance.

## How to Run
1. Place train.csv in the project folder.
2. Run the Python script:
   ```bash
   python house_price_prediction.py