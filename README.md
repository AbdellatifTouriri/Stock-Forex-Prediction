# Forex Exchange Rate Prediction using LSTM

This project utilizes LSTM (Long Short-Term Memory) neural networks to predict daily exchange rates for GBP/JPY and APPL based on historical data downloaded from Yahoo Finance.

## Overview

The project includes the following components:

- **Data Collection:** Daily forex data is collected using `yfinance` library for the GBP/JPY currency pair.
- **Data Preprocessing:** Data is cleaned, filled for missing values, and relevant features (`Open`, `High`, `Low`, `Close`, `Volume`) are selected.
- **Model Building:** LSTM neural network model is constructed using TensorFlow/Keras to forecast future exchange rates.
- **Model Training:** The model is trained on historical data, with evaluation metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and R-squared (R2 Score) computed.
- **Prediction:** Functionality is provided to predict exchange rates for new data inputs after scaling with `MinMaxScaler`.
- **Visualization:** Results are visualized using matplotlib to compare predicted versus actual exchange rates.

## Requirements

- Python 3.x
- TensorFlow
- yfinance
- pandas
- scikit-learn
- matplotlib
