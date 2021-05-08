# Unit 12—Tales from the Crypto

![image](https://user-images.githubusercontent.com/70607134/117537693-adde0880-afd0-11eb-8979-d551ebfedf8d.png)


## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Files

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

---

## Instructions

----

### 1 - Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

---

### 2 - Natural Language Processing

In this section, you will use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 

#### Tokenize

Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

#### N-grams

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

#### Word Clouds

Finally, generate word clouds for each coin to summarize the news for each coin.

![image](https://user-images.githubusercontent.com/70607134/117537706-c4845f80-afd0-11eb-932b-2e29f8ac2eb7.png)

![image](https://user-images.githubusercontent.com/70607134/117537720-dc5be380-afd0-11eb-9ff3-c414bdf2640c.png)



---

### 3 - Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![image](https://user-images.githubusercontent.com/70607134/117537738-ec73c300-afd0-11eb-81f6-85591996eb97.png)


![image](https://user-images.githubusercontent.com/70607134/117537754-01e8ed00-afd1-11eb-8f3f-e8792068d098.png)

---

## Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

---

## Hints and Considerations

The free developer version of the News API limits the total monthly requests, so be careful not to exceed the free limits.

---

## Submission

* Use the starter Jupyter Notebook provided to conduct the NLP analysis and host the notebook in a GitHub repository.

* In your GitHub repository, include a ReadMe file that uses Markdown to summarize your homework.

* Submit the link to your GitHub project to Bootcamp Spot.

---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
