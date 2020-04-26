# Newscrawler_virality-prediction

Firstly, we will crawl the news from a popular news website of your choice,I crawled from the Times of India website.
#Import all the necessary libraries
Set the URL for news website and start making request
Get the soup of articles on website using beautiful soup and fetch all the links present in soup in a variable
Download the article from the links using newspaper library
Regression model is used for predicting the virality of news
Download the Online News Dataset from UCI Repository
Load and split the data into x_train, y_train, x_test, y_test
We will use RandomForest Regressor for training our regression model
Now we should convert our crawled news into the format of our prediction model because we cannot simply provide just the text, we have to find features from the news text so that they can help to predict the virality.
Append all these features to a list and make a data frame out of it.
Use this data frame to predict the virality of news using our regression model.
