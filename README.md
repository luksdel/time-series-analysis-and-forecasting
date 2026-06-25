# Time Series Analysis and Forecasting

> End-to-end time series analysis and forecasting using classical statistical models and exponential smoothing techniques.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17FrpBwuh51uOAX3S8xvpfYqwQ_gt41q8?usp=sharing)

## Overview

This project presents a complete workflow for analyzing and forecasting the Brazilian Automotive Production Index using classical statistical time series techniques.

The notebook demonstrates every stage of a forecasting pipeline, including time series preparation, exploratory visualization, decomposition analysis, autoregressive modeling, seasonal ARIMA forecasting, exponential smoothing methods, and forecast comparison.

The objective is to understand the temporal dynamics of the series, identify trend and seasonal patterns, evaluate different forecasting approaches, and compare their effectiveness for short-term prediction.

## Objectives

- Prepare and regularize a monthly time series
- Perform exploratory time series analysis
- Decompose the series into trend, seasonal, and residual components
- Develop and evaluate an Autoregressive (AR) model
- Develop and evaluate a Seasonal ARIMA (SARIMA) model
- Apply exponential smoothing methods (SES and Holt)
- Compare forecasting techniques for short-term prediction

## Dataset

The dataset corresponds to the **Brazilian Automotive Production Index**, a monthly economic indicator published by the **National Association of Motor Vehicle Manufacturers (ANFAVEA)** and distributed through the **Central Bank of Brazil (BCB) SGS API**.

Unlike a simple vehicle production count, the indicator reflects the overall performance of the Brazilian automotive industry by considering production, inventories, dealership sales, vehicle commercialization, and motorcycle production.

| Attribute | Value |
|-----------|-------|
| Frequency | Monthly |
| Period | February 1993 – April 2026 |
| Source | Central Bank of Brazil (BCB) / ANFAVEA |

## Workflow

The notebook follows a complete time series forecasting workflow:

1. Time Series Preparation
2. Exploratory Time Series Visualization
3. Time Series Decomposition
4. Autoregressive (AR) Modeling
5. Seasonal ARIMA (SARIMA) Modeling
6. Exponential Smoothing Methods
7. Forecast Comparison

## Models Implemented

| Model | Description |
|--------|-------------|
| Autoregressive (AR) | Captures temporal dependence using lagged observations |
| Seasonal ARIMA (SARIMA) | Models trend, seasonality, and temporal dependence |
| Simple Exponential Smoothing (SES) | Forecasting based on the level component |
| Holt's Linear Trend | Forecasting with additive trend |
| Holt's Exponential Trend | Forecasting with exponential trend |
| Holt's Damped Trend | Forecasting with damped trend |
| Holt's Multiplicative Damped Trend | Forecasting with multiplicative damped trend |

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- SciPy
- Google Colab

## Repository Structure

```text
time-series-analysis-and-forecasting/
│
├── README.md
└── time-series-analysis-and-forecasting.ipynb
```

## Key Topics Covered

- Time Series Analysis
- Forecasting
- Time Series Decomposition
- Stationarity Testing
- Augmented Dickey–Fuller Test
- Autoregressive Models
- Seasonal ARIMA (SARIMA)
- Exponential Smoothing
- Holt's Method
- Residual Diagnostics
- Forecast Comparison
