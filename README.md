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

## Running project
- Before start please run required pip installs, packages imports, 'helper methods' and 'load and preprocessing of files'.
- Please do not run tweets download cells because it will cause errors due to Tweeter API problems 
- After these steps You can run the rest of the project (KMeans, Bert, Classic Models and Neural Networks)
- If the UTF-8 error occurs, please uncomment and run the very first cell of the project

## Data 
Data was obtained from Twitter using Tweepy for English and Polish language. Due to problems with API we decided to save it to the CSV files for future use.

Raw data files:
  - pis_raw.csv (PL data)
  - eurovision.csv (EN data)

Data contains:
- edit_history_tweet_ids
- id
- text

The most useful part of information from this data is 'text' which represents the content of the tweet. Tweets have been cleaned from characters that could influence the learning process, labelized, lemmatized and saved again to save time on processing them again. **It's a good idea to work on already processed data from files to save time on another processing process.**:

Processed files: 
  - tweets_with_labels_pl.csv
  - tweets_with_labels_en.csv

## K-means
### Polish language
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/9585e076-c9ab-4cfe-a4f7-49f440250105)

### English language
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/913b660e-a0e9-4900-b678-75045805a754)

## Bert
### Roberta


### Distilbert


## Clasic models
### Naive Bayes


### Support Vector Machine


### Logistic Regression


## Neural Networks
### LSTM


### BLSTM


### Convolutional Neural Network (CNN)

