# Stock Market Prediction with Sentiment Analysis

**Introduction**

This repository contains a Python application that combines financial stock data with sentiment analysis to predict stock prices.The model integrates sentiment scores derived from Twitter data regarding specific blue chip stocks, in this case, Tesla (TSLA), to enhance the stock price prediction accuracy using a Generative Adversarial Network (GAN).


**Features**

* Data Integration: Combines stock prices with sentiment analysis from Twitter.

* Sentiment Analysis: Uses VADER sentiment analysis to gauge the sentiment from tweets.
  
* Technical Indicators: Calculates various technical indicators such as Moving Averages, MACD, and Bollinger Bands.
  
* Machine Learning Model: Utilizes a GAN consisting of LSTM layers for stock price prediction.
  
* Visualization: Provides graphical representations of stock prices and predictions.
  

**Dependencies**

This project requires the following Python libraries:

* numpy
  
* pandas
  
* matplotlib
  
* scikit-learn
  
* TensorFlow/Keras
  
* NLTK
  
* statsmodels
  

**Dataset**

The data used in this project are derived from two main sources:

* Stock Prices: Historical stock prices obtained from Yahoo Finance (stock_yfinance_data.csv).

* Tweets: A dataset containing tweets related to various stocks (stock_tweets.csv).


**Usage**

Ensure that you have the stock_yfinance_data.csv and stock_tweets.csv files in the same directory as your script.


**Acknowledgements**

This project modifies and extends the work found in the Stock Prediction GAN Twitter Sentiment Analysis from Kaggle. Modifications include the integration of additional sentiment analysis and adjustments to the neural network architecture to adapt to the specifics of the stock data.

Special thanks to the creators of the VADER sentiment analysis tool, which is instrumental in processing the sentiment expressed in tweets.


