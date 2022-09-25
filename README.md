# Sentiment_Analysis_with_Bitcoin_reviews_from_tweets
tweet data is from https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets
![image](https://user-images.githubusercontent.com/90729733/192163750-5f8e36e8-b23e-4a91-b68d-ad375791e09c.png)
financial data for bitcoin is from https://ca.investing.com/crypto/dogecoin/historical-data
![image](https://user-images.githubusercontent.com/90729733/192163766-c785ccdd-0892-4f39-ac11-a4a69f72a7d0.png)

Since the tweets dataset is too large to loop through every record, it is more convenient to random select 30000 tweets to put into our model.
After simple data cleaning, I applied vader sentiment analyzer to generate sentiment scores for tweets.

Finally, I checked the correlation between tweets and price of bitcoin and try to use these data to predict the future price of bitcoin.
