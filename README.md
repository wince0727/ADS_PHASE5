# ADS_PHASE5

# Stock Price Prediction using Machine Learning

This project aims to predict the future prices of individual stocks or the overall stock market using machine learning techniques. By examining historical stock price data and considering market trends, economic indicators, and company-specific information, we can make informed estimates about the direction in which a stock price may move.

## Prerequisites

Before you can run this project, you will need to have the following software installed on your computer:

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Tensorflow
- Streamlit

You can install these packages using pip, the Python package manager. For example, to install Pandas, you can run the following command:

```
pip install pandas
```

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine using Git or download the ZIP file.
2. Open a terminal or command prompt and navigate to the project directory.
3. Install the required packages using pip, as described in the Prerequisites section.
4. Run the `main.py` file using the following command:

```
streamlit run main.py
```

5. This will launch a Streamlit app in your web browser, where you can interact with the stock price prediction model.

## Methodology

This project uses the following methodology to predict stock prices:

1. Data Collection: We collect historical stock price data from Yahoo Finance using the `pandas_datareader` library.
2. Data Preprocessing: We preprocess the data by cleaning it, removing missing values, and scaling it using the `MinMaxScaler` from Scikit-learn.
3. Feature Engineering: We engineer features from the data, such as technical indicators like Moving Averages, Relative Strength Index (RSI), Bollinger Bands, and MACD (Moving Average Convergence Divergence).
4. Model Training: We choose a suitable machine learning or statistical model for stock price prediction, such as linear regression, time series models (e.g., ARIMA or LSTM), or machine learning models like decision trees, random forests, or gradient boosting. We split the data into training and testing sets, train the model using the training data, and fine-tune hyperparameters for better performance.
5. Making Predictions: We use the trained model to make predictions on the testing data or future data.
