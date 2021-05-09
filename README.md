You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

---

### Files

[Crypto Sentiment Notebook](crypto_sentiment.ipynb)

---

### Instructions

#### Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.


#### Natural Language Processing

In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

#### Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.

---

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)


### Results

Q: Which coin had the highest mean positive score?

> A: Ethereum had a slightly higher mean positive score. (.0597 compared to .0576)

Q: Which coin had the highest compound score?

> A: The coin with the highest compound score is also ethereum. (.8271 compared to .8126)

Q. Which coin had the highest positive score?

> A: Bitcoin had the highest positive score. (.269 compared to .256)

## Bitcoin Word Cloud
![btc-word-cloud.png](Images/bitcoin_wc.png)

![eth-word-cloud.png](Images/ethereum_wc.png)