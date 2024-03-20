# Stock_prediction
Stock Prediction with Gradient Boosting Regressor


# Stock Prediction with Gradient Boosting Regressor

## Introduction
This Python script enables users to predict stock prices using historical data and the Gradient Boosting Regressor algorithm. It provides functionalities for downloading historical stock data, feature engineering, model training with hyperparameter tuning, evaluation, and visualization of predictions.

## Usage
1. **Install Dependencies**: Before using the script, ensure you have the necessary dependencies installed. You can install them using pip:


2. **Run the Script**: Run the Python script `stock_prediction.py`:


3. **Follow Instructions**: Upon running the script, you'll be prompted to input the stock ticker symbol for which you want to predict the prices. Enter the desired stock ticker symbol (e.g., AAPL for Apple Inc.). The script will download historical data, train the model, evaluate its performance, and visualize predictions.

## Functionalities
1. **Downloading Historical Data**: The script downloads historical stock data using Yahoo Finance API (yfinance) based on the provided stock ticker symbol and date range.
2. **Feature Engineering**: Feature engineering is performed to create additional features from the historical data, including Simple Moving Averages (SMA), Volatility, and Returns.
3. **Model Training with Hyperparameter Tuning**: The script trains a Gradient Boosting Regressor model using historical stock data. Hyperparameters are tuned using Grid Search Cross Validation to find the best combination for optimal performance.
4. **Model Evaluation**: The trained model's performance is evaluated using Mean Squared Error (MSE) metric on a test set.
5. **Visualization of Predictions**: The script visualizes the actual vs. predicted stock prices using Matplotlib.

## Documentation
The script is documented to guide users through its functionalities and usage. Each function within the script is accompanied by comments explaining its purpose and usage.

## Requirements
- Python 3.x
- Dependencies: yfinance, scikit-learn, matplotlib, pandas

## Author
- Created by Muzammil Muzaffar


