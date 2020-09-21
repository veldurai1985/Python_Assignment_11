# LSTM Stock Predictor

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

1. Prepare the data for training and testing
2. Build and train custom LSTM RNNs
3. Evaluate the performance of each model

- - -

### Files

[Closing Prices Notebook](lstm_stock_predictor_closing.ipynb)

[FNG Notebook](lstm_stock_predictor_fng.ipynb)

- - -

### Evaluate the performance of each model

> Which model has a lower loss?
* Stock price prediction based on closing price (loss = 0.0204/Window size =1) has lower loss than stock price prediction based on FNG (loss = 0.1151/Window size =1).

> Which model tracks the actual values better over time?
* Stock price prediction based on closing price tracks the actual values better over time.

> Which window size works best for the model?
* The window size 1 has the lowest loss compared to other window size. In stock price prediction based on close, 
Window size loss for 10  = 0.0487 vs Window size loss for 1 = 0.0204

- - -
