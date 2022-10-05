# Ukraine-Russia-War-Twitter-data-Analysis
This project analyzes the retweet proneness of tweets on the subject based on their text using NLP.

Russia’s invasion of Ukraine in February 2022 was a major point of escalation in the Russo-Ukrainian War. This is currently the largest war in Europe since World War II 
and has been a main topic in the news. Many people have flooded the Internet with social media posts regarding this conflict, and some of these posts have gone viral. 
Social media, being as powerful as it is, can be pivotal to making lasting impacts in geo-politics, economics, etc. So, we decided to analyse what type of posts are more 
prone to being popular, in terms of getting retweeted. Additionally, we analyzed if the otherwise powerful statistics like number of followers, etc. have the same 
"power" in predicting retweet proneness when we have an event larger than an individual. 
In this project, we focus on analyzing public Twitter posts and responses across the world regarding this conflict to predict the degree of virality of a tweet. 
Specifically, we performed classification models such as Logistic Regression, Decision Trees and 
Random Forest to predict fixed retweet count bins/groups, which were created specifically to have the problem as a classification problem. The classification models were 
compared via accuracy and F1 score. We also performed regression models such as Decision Trees and Random Forest regressor to predict the retweet count. The regression 
models were compared via root mean squared error (RMSE) and mean absolute error (MAE). We used the text feature, tweet texts, to predict popularity. This feature was 
further processed by performing the following natural language processing techniques: stemming, bag-of-words, and Term Frequency-Inverse Document Frequency (TF-IDF). 
The results indicated that for the classification problem, the logistic regression model performed the best in predicting the tweet popularity with the testing 
accuracy of 87.01%, and Decision Trees performed better in the regression setting
