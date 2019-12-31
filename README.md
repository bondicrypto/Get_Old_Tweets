# Get_Old_Tweets
A guide for downloading Twitter data using the Python package GetOldTweets

I should start out by saying that the most robust approach for downloading Twitter data is to go to the source, sign up for a developer license with Twitter and access their API directly using Tweepy. This guide is intended for one of the following:
Seeking to do some quick and simple analysis with Twitter data (this code can be executed in less than 10 minutes)

Needing access to Tweets older than 1 week (the Twitter API only serves Tweets from the past week)

A large volume of Tweets (Twitter API limits the number of Tweets you can download after around 3,000)
