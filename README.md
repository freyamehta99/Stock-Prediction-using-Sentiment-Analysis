# Stock-Prediction
Honors Research Project - Implemented an LSTM RNN to predict an individual company's future stock prices.

SUPERVISED LEARNING (SA)

Sentiment analysis is a method to understand public attitude towards a topic/product (here stocks).
Approach - RSS feeds for effective prediction - doing sentiment analysis (mining) on the RSS news feeds play a major role in stock price prediction. 

Collect thousands of tweets - predict/determine if the tweet is bullish or bearish.
Or/and get data from news api like intrinio and NY Times and give each set a rate of positivity (range: 1- 10)
Use this set of data to predict the positivity of current news and effectively predict the stock price.

Using RNN (Recurrent Neural Network):
Price of the stock on a particular day depends on previous n days of price of the stock. 
How to train the RNN? We can train the RNN using gradient descent (start with random parameters of the model and train using GD to build a good model).

