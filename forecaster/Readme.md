# Visitor Prediction Model for a Leisure Attraction

This project aims to predict daily visitor counts (`label`) for a leisure attraction located at the border of two counties in Germany. The dataset includes factors such as school holidays, bank holidays, and daily weather data. The goal is to use machine learning models to accurately predict visitor numbers and evaluate model performance using the Root Mean Squared Error (RMSE) metric.

## Features and Data
- **School Holidays**: Encoded as 0-3 (no holidays, holidays in specific counties, or both counties).
- **Bank Holidays**: Encoded similarly to school holidays.
- **Weather Data**: Daily weather features for the location.
- **Target Variable**: `label` (daily visitor count).

## Methods
1. Data preprocessing: Merging datasets, handling missing values, feature scaling.
2. Models:
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
3. Evaluation: RMSE calculation and feature importance analysis.
4. Visualization: Comparison of true vs. predicted values.

## Results
The Random Forest and Gradient Boosting models are compared based on their RMSE to determine the best-performing model for visitor prediction.

## Usage
This project demonstrates the use of machine learning for predictive analytics in decision-making scenarios, such as optimizing resources or planning marketing campaigns.

Feel free to clone the repository and modify the code to suit your own datasets and objectives.
