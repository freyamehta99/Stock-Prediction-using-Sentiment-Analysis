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

Opinions are central to almost all human activities and are key influencers of our behaviors. When people make a decision they often refer to the opinions of others. This is true not only for individuals but also for organizations. It is known that the stock market is made up of individuals. Individuals’ market behaviors will be affected by their own mood states [4], and the public mood state is reflected by individual’s mood state.
Thus, stock market shall have some relation with public mood state.  Mining public mood states is an excellent area for sentiment analysis.
Given a stock price time series, for each time interval we classify price movement as "up," "down," or (approximately) "unchanged" relative to the volatility of the stock and the change in a relevant index. 