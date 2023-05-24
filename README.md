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

## Project Overview
In our project, we trained several models to analyze the sentiment of a tweet in polish and english language. </br>
First, we downloaded our training set using Tweepy. Then we refactor our data and labeled it. </br>
After processing our data to csv to save time running previous code, which takes a while.

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
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/5161cf91-5e0d-4298-bd78-1849b5aa71f4)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/ec4a9296-f9ca-4a70-906b-0b7152db74ce)


### Distilbert
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/253a4b33-d0bf-4871-8381-66aa262c718c)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/3c21e228-f3eb-4165-9962-16b8054ac541)

## Clasic models
### Naive Bayes
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/564a437c-3772-46dc-bbf8-b71f2c63de95)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/d5487290-9617-4180-baa0-f0e230c51d59)

### Support Vector Machine
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/2c1c74f7-1e05-47d3-81d1-7e1315994513)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/bfb12a0d-7ec2-4e50-8285-0a92a7b836fd)

### Logistic Regression
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/eaf3b9d6-e313-4379-b31b-bd4d06ea1956)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/61686885/f6705ccf-89ba-4277-93e8-4c0ab93ddb4e)

## Neural Networks
### LSTM
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/213d32ec-2376-4b2a-a589-0e4ff087f281)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/97484ccd-2c2c-42de-8cd4-416b8c621bda)

### BLSTM
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/a0adba33-29a8-4725-8103-75a83241cb96)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/30324d10-4e06-4299-900e-47546aa95e32)

### Convolutional Neural Network (CNN)
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/2c09d64d-9b17-45e9-b7df-0400cf427ff0)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/bfe8cc6f-8b74-449d-a16b-8343bb49018f)
