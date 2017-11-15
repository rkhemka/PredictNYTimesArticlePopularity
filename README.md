# PredictNYTimesArticlePopularity
Data Science: Predicting which New York Times blog articles will be the most popular

Project Description:
The project is to develop an analytical model which predicts whether each New York Times articles will be popular or not.

We are going to use 6532 articles as training set, and 1870 for testing set.
Each training set has 8 features like "NewsDesk","SectionName", 
"SubsectionName","Headline","Snippet","Abstract","WordCount","PubDate",
and 1 label of "Popular".
If any feature value is missing, we will be replacing it by either mean value or with most common string found. 

Getting Data:
We have found a GitHub source from where we have extracted the dataset.



Goal:
To predict if testing set popular will be 0 or 1 by using KNN,
decision tree, etc.

https://www.kaggle.com/c/15-071x-the-analytics-edge-competition-spring-2015
