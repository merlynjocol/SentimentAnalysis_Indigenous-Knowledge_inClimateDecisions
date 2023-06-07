# Twitter Sentiment Analysis
# Opinions on Indigenous Knowledge in the main Climate Decision-making Spaces. 
## Period of analysis: 2009 - 2023

<img src="https://www.iitc.org/wp-content/uploads/COP-26-Traditional-Knowledgeholders-session.jpg"  width="60%" height="30%">
Source: https://www.iitc.org/

## Objetive: 

This study is done ubnder the WOMER project to explore opinions, entities and interest on Indigenous Knowledge in the main Climate Decision-making Spaces.
For the sentiment analysis, I used four distinct natural language processing models to collect and categorize Twitter user opinions about Indigenous Knowledge in the main climate decision spaces.
You can find the libraries, approach and some early results in this file. 
For a more detailed analysis, please check the files of the different analysis done (text and sentiment analysis).

## Main climate decision spaces included in the analysis

```
- UN Convention on Biological Diversity (CBD) 
- Conference of the Parties serving as the meeting of the Parties to the Kyoto Protocol (CMP)
- Paris Agreement
- Kyoto Protocol
- Conferences of the Parties (COP)
- Subsidiary Body for Scientific & Technological Advice (SBSTA)
- Subsidiary Body for Implementation (SBI)
- Intergovernmental Panel on Climate Change (IPCC)
- G8 
- G20
- Major Economies Forum on Energy and Climate (MEF)
- Organisation for Economic Cooperation and Development (OECD)
- International Energy Agency (IEA)
```

# Results Text Analysis


## Top10 Tweets with more likes ❤️
![tpo10_likes](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/a95e6a6768baf990212dcbe434578ccfab9e9f0b/images/top10_tweetsLike.png)

![tpo10_likes](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/217bfb5eed81ff8400db9329d9dd71619675dd17/images/TextAnalysis_ind_more_likes.png)


## Top10 Hashtags used that mention indigenous knowledge in a climate decision-making space
<img src="https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/f0246af568a4b45ec70822590e606f57e80c551b/images/TopHashtag.png"  width="60%" height="30%">

![tpo10_hashtag](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/f0203b372aba9b94b779bbb811ba5aa639c86de6/images/TextAnalysis_More_Hashtags.png)

## Top10 organizations mentioned
<img src="https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/main/images/TopMentions_2charts.jpg">

<img src="https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/f0203b372aba9b94b779bbb811ba5aa639c86de6/images/TextAnalysis_More_mentions.png">


# Results of the Sentiment Analysis: Model outputs

## 1. VADER (Valence Aware Dictionary and sentiment Reasoner)

![vader1](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/c06c48b62cf3f615f066bc4c2e228ae92a66dcfb/images/vader_results.jpg)



## 2. Roberta 
![roberta](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/5b2e66d2ead4350617fe488463697f368a754786/images/Roberta_sentiment_analysis.png)

## 3. Transformers

![transformers](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/b2ac8115e93703a4310eda1ddb46d9b162a2c92f/images/transformers_sentiment_a.png)

## 4. TextBlob
![textblob](https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/b2ac8115e93703a4310eda1ddb46d9b162a2c92f/images/TextBlob_Sentiment_analysis.png)


# Results of the frequent words used in tweets 

## Model WordCloud

<img src="https://github.com/merlynjocol/SentimentAnalysis_Indigenous-Knowledge_inClimateDecisions/blob/b2ac8115e93703a4310eda1ddb46d9b162a2c92f/images/Wordcloud_all_tweets.png" width="60%" height="30%">

# Process

- Scraping Tweets

- Exploratory Data Analysis

- Data cleaning

- Tokenization of tweets

- Sentiment Analysis using 5 different NLP models

- Data Visualization


# Tools
```
Python
Pandas
Numpy
Matplotlib
Seaborn
Snscrape (Scraper for social networking services)
NLTK (Natural Language Toolkit)
VADER (Valence Aware Dictionary and sEntiment Reasoner)
RoBERTa (Robustly Optimized BERT Approach)
Transformers Pipeline
TextBlob
WordCloud
```

