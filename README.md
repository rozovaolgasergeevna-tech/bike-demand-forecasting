# Bike Demand Forecasting

Hourly bike rental demand forecasting using nonlinear regression models.

## Project Description

This project aims to predict the number of bike rentals for each hour. Accurate demand forecasting helps to:

- Optimize bike distribution across stations
- Prevent shortages during peak hours
- Reduce operational costs for fleet rebalancing

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost / LightGBM / CatBoost
- Optuna (hyperparameter optimization)

## Data

The dataset includes historical hourly data on:

- Number of bike rentals
- Weather conditions (temperature, humidity, wind speed)
- Time features (hour, day of week, season, holidays)

## Models Compared

The following approaches were evaluated:

- Linear Regression (baseline)
- Random Forest
- XGBoost
- LightGBM
- CatBoost

## Results

| Model | RMSE | R2 |
|-------|------|-----|
| Linear Regression | X.XX | X.XX |
| Random Forest | X.XX | X.XX |
| LightGBM (optimized) | X.XX | X.XX |

Note: Replace X.XX with actual metrics from your model.

## Installation and Usage

Clone the repository:

```bash
git clone https://github.com/rozaovalgasergeevna-tech/bike-demand-forecasting.git
cd bike-demand-forecasting
