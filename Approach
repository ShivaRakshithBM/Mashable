Problem statement:
Identification of the news articles which will be popular among the public for Mashable company

Questions:
1) What are the factors to include for determining the popularity of the news articles?
2) What is the metric to determine the popularity of the news articles?

Approach:
Followed the 6 stage framework of CRISP Data Mining process

Business understanding:

1) Mashable is a content (news articles) sharing platform which has its location in countries of USA, Australia, Canada
2 The users can share the articles in social networking platforms such as Facebook and Twitter. The more number of shares the article earns, the more is the impressions for the Mashable brand
3) Predictting the lnumber of shares (which indicates its popularity) helps them to provide the users with popular and personalized targeting of the users 

Data understanding

1) The dataset consists of 39,797 instances, each corresponding to a different article, and 61 attributes (58 predictive attributes, 2 non-predictive attributes, 1 target attribute)
2) The data includes both numeric as well as binary attributes, of which 58 predictive attributes can be classified to 8 aspects: words counts, content diversity, data channel, weekday at publish and sentiment
3)  

1) Obtained the dataset from  UCI machine learning repository published by Mashable during the years 2013 - 2015
2) Had 63 variables like # of images, # of videos, # of words in the article, category of the article, , sentiment polarity, Title Polarity etc.
 words counts, content diversity, data channel, keyword shares, referenced articles 
shares, weekday at publish, topics and sentiment
3) The target varia

Data Preperation:

1) Normalization: I had to get all the variables into a standard range and give equal weightage to all of them in our predictions. I have implemented the min - max normalization

2) Log transformation
plotting the distribution of target variable -- number of shares, I noticed that it was right-skewed, so I did log transformation to reduce the skewnes

Mdelling:
1) 

Evaluation:
1) I have used Cross validation of 10 folds. The model has been implemented to hold out data sets. 
2) Have used the metric Root Mean Square Error to evaluate the difference of Actual and predicted number of shares
3) Baseline -

Deployment:
1) The analysis ccan be used by deploying thhe same in Mashable. Multiple users can access if its on a cloud sharing platform like AWS or R server
2) It can also be automated so that on a daily basis when the data changes, the predictions can be produced and used. We can connect the model to the platform from where the data is stored
