# Electricity Demand Forecasting: Baseline vs. LSTM Model

This project demonstrates electricity demand forecasting using two different models: a baseline Linear Regression (LR) model and a Long Short-Term Memory (LSTM) model. The goal is to predict electricity demand based on historical consumption data, evaluating the performance of both models using metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Overview
Electricity demand forecasting is essential for optimizing energy production and ensuring efficient distribution. This project compares a simple machine learning model (Linear Regression) with a more advanced deep learning model (LSTM) to predict electricity demand.

### Key Features:
- **Data Preprocessing**: Includes handling missing values, resampling the data to hourly intervals, and feature engineering (creating lag features).
- **Model Comparison**: Compares Linear Regression and LSTM models using evaluation metrics such as MAE and MSE.
- **Visualization**: Displays a graph comparing actual and predicted electricity demand using the LSTM model.
- **Time Series Forecasting**: Utilizes historical demand data and temporal features (hour, day of the week, month) for accurate forecasting.

## Dataset
The dataset used in this project is the **LD2011_2014.txt** file from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00321/). The data contains electricity consumption readings recorded every 15 minutes, which are then resampled to hourly data for the analysis.

## Installation

1. Clone the repository:
   ```bash
   git clone 
   cd electricity-demand-forecasting