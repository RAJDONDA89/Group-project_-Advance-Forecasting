# Group Project — Advanced Forecasting

## Project Overview

This project focuses on forecasting monthly car sales using time series forecasting methods. The aim is to compare classical and advanced forecasting models using a consistent dataset, validation strategy, and evaluation metrics.

The project follows the full forecasting workflow, including data exploration, preprocessing, model implementation, model tuning, evaluation, and interpretation.

## Dataset

The dataset used is the Monthly Car Sales dataset.

- Frequency: Monthly
- Time span: 1960 to 1968
- Target variable: Sales
- Forecast horizon: 12 months

The dataset is stored in the `Data/` folder.

## Forecasting Task

The objective is to forecast monthly car sales for the final 12 months of the dataset.

The final 12 observations are used as the test set, while all earlier observations are used for training.

## Models Used

Each group member implements one different forecasting model:

| Student | Model | Baseline |
|---|---|---|
| Student 1 | ARIMA | Naive Forecast |
| Student 2 | SARIMA | Seasonal Naive Forecast |
| Student 3 | LSTM | Mean Forecast |

## Project Structure

```text
Group-project_-Advance-Forecasting/
│
├── Data/
│   ├── monthly-car-sales.csv
│   └── cleaned_sales_data.csv
│
├── Notebooks/
│   ├── Group_EDA_Data_Preparation.ipynb
│   ├── ARIMA.ipynb
│   ├── SARIMA.ipynb
│   └── LSTM.ipynb
│
├── README.md
└── requirements.txt