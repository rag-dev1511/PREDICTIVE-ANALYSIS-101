# Predictive Analytics Using Historical Data

Forecasting monthly airline passenger counts (1949-1960) using the seaborn "flights" dataset.

## Approach
- Cleaned and preprocessed the data (datetime conversion, missing value and duplicate checks)
- Split chronologically: train 1949-1958, test 1959-1960
- Models: Linear Regression (trend + month dummies) and Holt-Winters
- Evaluated with MAE, RMSE, and R2, and visualized predictions and a 24-month forecast

## Results
| Model | MAE | RMSE | R2 |
|---|---|---|---|
| Linear Regression | 34.64 | 47.94 | 0.588 |
| Holt-Winters | 28.98 | 32.49 | 0.811 |

## Files
- predictive_analytics_flights.ipynb: full notebook with code, outputs, and plots
BY - RAG
