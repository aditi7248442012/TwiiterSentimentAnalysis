TWITTER SENTIMENT ANALYSIS:
ABSTRACT:
This project addresses the problem of sentiment analysis in twitter; that is classifying tweets according to the sentiment expressed in them: positive, negative or neutral. The project made use of methods from various classes inside the tweepy API, which allows us to very easily stream tweets in real time directly from twitter. Textblob have been used to test the sentiment of the extracted tweets.
WHAT I HAVE DONE:
The tweets from a particular twitter handle are tested to be positive, negative or neutral. 
HOW I HAVE DONE:
The project made use of python language and various python libraries. Firstly, when we want to analyze the tweets, we need to have a twitter account and to access tweets to analyze them, I have created a twitter application (developer.twitter.com) to get some credentials like access token, consumer key, etc. that are used to authenticate with the user client. The tweets are extracted by providing the twitter handle of particular person (eg. narendramodi, BarackObama, etc.). The no. of tweets to be extracted and printed is given to the program. I made use of re (regular expression) library to clean tweets of any hyperlinks or extra character (any unwanted character that does not contribute in testing the sentiment of that tweet, is eliminated). The polarities of the sentiments of the cleaned tweets are tested.
CONCLUSION: 
The project is successful in accessing tweets of any twitter handle and in judging them on basis of positive, negative or neutral feelings/emotions. 
