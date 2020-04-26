# Newscrawler_virality-prediction

1)Firstly, we will crawl the news from a popular news website of your choice,I crawled from the Times of India website.

2)Import all the necessary libraries

3)Set the URL for news website and start making request

4)Get the soup of articles on website using beautiful soup and fetch all the links present in soup in a variable

5)Download the article from the links using newspaper library

6)Regression model is used for predicting the virality of news

7)Download the Online News Dataset from UCI Repository

8)Load and split the data into x_train, y_train, x_test, y_test

9)We will use RandomForest Regressor for training our regression model

10)Now we should convert our crawled news into the format of our prediction model because we cannot simply provide just the text, we have to find features from the news text so that they can help to predict the virality.

11)Append all these features to a list and make a data frame out of it.

12)Use this data frame to predict the virality of news using our regression model.
