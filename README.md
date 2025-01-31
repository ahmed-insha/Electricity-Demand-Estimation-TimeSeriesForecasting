# Electricity-Demand-Estimation-TimeSeriesForecasting

## Objective

The goal of this project is to build and evaluate different time series forecasting models to predict electricity consumption for the next 1-2 years. Various models, including ARIMA, SARIMA, ETS, AutoARIMA, and Prophet (Darts), are compared to identify the best-performing model based on RMSE, MAPE, and RMSPE.

## Description

In this repository, you will find scripts to:

- Prepare the electricity consumption data.
- Train and evaluate multiple forecasting models.
- Compare the performance of these models using different error metrics.
- Use the Prophet (Darts) model for the final forecasting, which has been selected based on superior performance.

### Key Features:
- Data preprocessing and feature engineering.
- Model building and evaluation (ARIMA, SARIMA, ETS, AutoARIMA, Prophet).
- Forecasting and demand estimation for the next 1-2 years on a monthly basis.
- Evaluation using RMSE, MAPE, and RMSPE metrics.

## Getting Started

### Prerequisites

To run this project, you will need to have Python installed along with the following packages:

- `darts`
- `prophet`
- `numpy`
- `pandas`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install darts prophet numpy pandas matplotlib
```

### Files

- **data/**: Contains the historical electricity consumption data.
- **models/**: Contains scripts for training and evaluating different forecasting models.
- **output/**: Stores the forecasted results for the next 1-2 years.


## Model Evaluation

The models are evaluated based on the following metrics:

- **RMSE** (Root Mean Squared Error)
- **MAPE** (Mean Absolute Percentage Error)
- **RMSPE** (Root Mean Squared Percentage Error)

The Prophet (Darts) model outperforms the other models in terms of these metrics, making it the best choice for the electricity demand forecasting task.

## Conclusion

Prophet (Darts) was selected as the best model due to its ability to handle seasonality and trends effectively, its robustness to missing data, and its scalability. It provides reliable demand forecasts for the next 1-2 years.

-
