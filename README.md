# Predict_Disaster
## Description

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this task, we have to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified.


## Directory Structure
- [predict_disaster_with_roberta_cTF_IDF.ipynb](./predict_disaster_with_roberta_cTF_IDF.ipynb):Notebook contains detailed steps taken for modelling the tweets related to disater data
- [train.csv](./train.csv): the training set, which includes the labeled tweets.
- [test.csv](./test.csv): the test set; your task is to predict the tweets available in test file
