# SentitemtRecognition
Sentiment recognition made in Python.

### Made by 
Bartłomiej Stocki - S18977

Marcin Wałachowski - S19541

Wiktor Androsiuk - S16838

## Methods used
- K-means
- Bert
  - Roberta
  - Distilbert
- Classic Models 
  - Naive Bayes
  - Support Vector Machine
  - Logistic Regression
- Neural Networks
  - LSTM
  - BLSTM
  - Convolutional Neural Network (CNN)

## Data 
Data was obtained from Twitter using Tweepy for English and Polish language. Due to problems with API we decided to save it to the CSV files for future use.

Raw data files:
  - file_pl.csv
  - file_en.csv

Data contains:
- edit_history_tweet_ids
- id
- text

The most useful part of information from this data is 'text' which represents the content of the tweet. Tweets have been cleaned from characters that could influence the learning process, labelized, lemmatized and saved again to save time on processing them again. **It's a good idea to work on already processed data from files to save time on another processing process.**:

Processed files: 
  - tweets_with_labels_pl.csv
  - tweets_with_labels_en.csv

