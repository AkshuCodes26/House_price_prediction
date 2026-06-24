# Boston House Price Prediction

## Project Overview
Predicts the median house price in Boston using Machine Learning
based on various features like crime rate, number of rooms,
location, and more.

## Project Structure
- Day 1 → Dataset Understanding + Preprocessing
- Day 2 → Exploratory Data Analysis (EDA)
- Day 3 → Feature Engineering + Data Preparation
- Day 4 → Model Building + Evaluation

## Dataset
- Source: Kaggle — Boston House Price Data
- Records: 506 rows
- Features: 13 columns

## Key Features Used
| Feature | Description |
|---------|-------------|
| CRIM    | Crime rate per town |
| RM      | Average number of rooms |
| LSTAT   | % Lower status population |
| TAX     | Property tax rate |
| PTRATIO | Pupil-teacher ratio |
| DIS     | Distance to employment centre |

## Model Used
- Ridge Regression (L2 Regularization)

## Results
| Metric | Value |
|--------|-------|
| R² Score | 0.68+ |
| MAE      | 3.18  |
| MSE      | 22.97 |
| RMSE     | 4.79  |

## Libraries Used
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## What We Predict
Input  → House features (rooms, crime rate, location etc.)
Output → MEDV = Median House Price (in $1000s)

Example:
  RM = 6.5 rooms, low crime area
  → Predicted Price = $28.5k

## Outcome
Successfully predicts Boston house prices using
Ridge Regression with feature engineering.
