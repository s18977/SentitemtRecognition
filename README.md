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
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/f284705a-164f-4aca-ad39-8a5325ad7bd7)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/593af571-565a-4a98-8b3f-c1488cdcfe7a)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/b02773fb-d7e9-42b0-aab0-04ecbec8ffed)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/f363efe8-6695-445d-9760-796a5d91bcbc)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/649402dc-7544-4bab-8bbe-0a9ab95ab0b6)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/5baaa6d3-2513-4a2f-8474-be2959d89086)

### Support Vector Machine
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/3407b18b-c824-491e-8c75-a6b65fadb188)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/7f1ab02a-2955-4313-8715-8bbc566fb2f3)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/a95c17dd-16c2-4f7d-8e93-ab5c6a965e34)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/cd094441-54eb-4443-93f6-557e07c62f03)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/21e6289d-dd9a-4379-a217-e23ab1b89442)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/76e6c7a2-4f15-494f-a1a1-44076e415420)

### Logistic Regression
#### Język Polski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/22e2a3c3-7cdb-44d0-9ec3-f8dd362f31d5)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/e1e999e6-c256-4408-a466-5ca660d7ce3c)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/768fe3d1-d47d-4ef1-bab0-589f465d4d61)

#### Język Angielski
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/a96aa6e4-53a1-4df9-8ec1-f707d96a8ba1)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/0f3fb5af-91ad-4ae2-8100-82b500fe2188)
![image](https://github.com/s18977/SentitemtRecognition/assets/44446716/a63f31d2-4f1f-4585-b247-b77d0ab6c257)

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
