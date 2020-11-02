# Stock Market Prediction using news sentiment and LSTM

Kindly refer to the StockPredictionModelv3.ipynb file for the detailed explaination and results

## Overview:

Using sentiment analysis and recurrent neural network models (LSTM)
we combine ”public sentiment” and historical market data to find a predictor for ”market movment”. We use financial news datasets from Reuters to predict public mood given by the sentiment of the news headline. In addition, we use Dow Jones Industrial average closing price to predict next day movement. The model trained with time series features for the period '2006-10-20' to '2008-01-17' obtain ~%95 accuracy on the test set from '2008-01-17' to '2008-02-28 using the window size of 32 days.

Data Sets:
Reuters Finacial News Data Set: https://github.com/duynht/financial-news-dataset
Dow Jones Industrial average data from yfinance

# The notebook is briefly summarized as follows:

Financial news-data prepration and sentiment analysis

Clean, standardize and merge historical data, merging news sentiment and price data

Visualizing the news sentiment and the historical data

Time series preperation and training/evaluation of the LSTM network 

