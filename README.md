# Introduction

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). This is the repository for team BEAR in the Kaggle [Competition Real or Not? NLP with Disaster Tweets] (https://www.kaggle.com/c/nlp-getting-started). The purpose of this competition is to build a model that predicts which Tweets are about real disasters and which one’s aren’t.
Data

The dataset contains trai and test sets. In the train and test sets there are about 10000 tweets that were hand classified (about real disaster or not). Each sample in the train and test set has the following information:

    The text of a tweet
    A keyword from that tweet (although this may be blank!)
    The location the tweet was sent from (may also be blank)

We are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

The files in the data folder are:

    train.csv - the training set
    test.csv - the test set
    sample_submission.csv - a sample submission file in the correct format
