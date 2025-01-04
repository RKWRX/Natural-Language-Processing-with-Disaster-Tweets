# Natural-Language-Processing-with-Disaster-Tweets
In this competition, I will build a recurrent neural network model that predicts which Tweets are about real disasters and which one’s aren’t. 

I have access to a training dataset of 7,613 tweets that were hand classified. 3,263 tweets are in test dataset. Each training data point includes following features.

* id - a unique identifier for each tweet
* text - the text of the tweet
* location - the location the tweet was sent from (may be blank)
* keyword - a particular keyword from the tweet (may be blank)
* target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

Note: keyword and location might be blank for some data point
