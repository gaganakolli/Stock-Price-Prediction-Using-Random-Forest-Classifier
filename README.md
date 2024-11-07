# Stock Price Movement Prediction using Random Forest Classifier

This project focuses on predicting daily stock price movements (rise/fall) for the S&P 500 based on historical data. By using machine learning techniques, particularly a Random Forest Classifier, the model aims to assist in forecasting whether the stock price will increase or decrease the next trading day.

## Project Overview
The model predicts stock price movements using historical S&P 500 data retrieved via the `yfinance` API. The dataset includes features such as closing price, trading volume, and rolling averages across different time frames. This approach allows us to capture trends and potential indicators for price movement.

Key features:
- **Data Retrieval**: Downloaded historical stock data using the `yfinance` API.
- **Feature Engineering**: Generated features such as rolling averages and trend indicators for various time horizons.
- **Model Training**: Trained a Random Forest Classifier with 100 estimators, fine-tuning hyperparameters for balanced accuracy and computational efficiency.
- **Model Evaluation**: Achieved a precision score of 0.56 and accuracy around 56%, demonstrating moderate predictive power.

## Technology Stack
- **Python**: Data processing and model development
- **Pandas**: Data manipulation and feature engineering
- **Scikit-Learn**: Model training and evaluation (Random Forest Classifier)
- **yFinance API**: Historical data retrieval
- **Matplotlib**: Data visualization and backtesting

## Usage
- **Data Retrieval**: Run the script to download historical data and create necessary features.
- **Model Training**: Train the Random Forest Classifier on the processed dataset.
- **Prediction**: Use the model to predict the next day's stock price movement (rise/fall).

