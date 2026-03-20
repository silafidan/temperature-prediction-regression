# temperature-prediction-regression
Temperature prediction using CatBoost and LightGBM on Madrid weather data.
# Temperature Prediction (Regression)

## Overview
This project focuses on predicting daily average temperature using regression models on historical weather data from Madrid (1997–2015). The dataset includes meteorological variables such as humidity, pressure, wind speed, visibility, and precipitation.

## Methods
Boosting-based regression algorithms, CatBoost and LightGBM, were used to model the relationship between meteorological features and temperature.

## Data Preprocessing
- Date feature extraction
- Missing value imputation using median
- Removal of categorical variables

## Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

## Results
CatBoost outperformed LightGBM by achieving lower error values and higher explanatory power.

## Technologies
- Python
- Pandas
- Scikit-learn
- CatBoost
- LightGBM
