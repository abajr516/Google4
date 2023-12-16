# Google 4
Summary:
The data we would use is from a real e-commerce website - Google Merchandise Store. We would want to predict the total revenue (i.e. natural log of the sum of all transactions) a user would bring in in the future on this website. 

Context:
Information about its users is very important for, businesses to plan their investments. According to the 80-20 rule, also known as the Pareto Punciple. 80% of a business's revenue comes from 20% of its users. Businesses spendra lot of money on marketing and their ROl (return on investment) would be higher by targeting those 20% users. For this purpose a lot of businesses use Google Analytics 360 as a tool to gain valuable insight from their data. This problem statement uses sample public data from GA360 and is a representation of work' Data Scientists in such businesses do to plan investment and-marketing strategies. 

Approach:
We would first start with Exploratory Data Analysis to answer a few questions using the data, as well as perform Feature Engineering to find the best subset of features for our use case. This would include pre-processing techniques such as normalizing the data, one-hot encoding, etc. The last step would be to choose which ML model would give us a good outcome, and training and testing the model. There can be various approaches to this problem. While Decision Tree Regressor might be a common choice, students can compare the functioning of different Boosting Machines on a metric they decide (such as RMSE). A variation to the problem statement can be to predict if a user would or would not make a purchase (in a more binary or regression based approach), rather than predicting the total revenue a user would bring. 

ML Problem Types: 
Supervised Learning. Classification, Supervised Learning. Regression 

Real or Representative: 
It is a representative project for educational - purposes 

Dataset Description:
https://support.google.com/analytics/answer/636734 2#about&zippy=962Cin-this-article 
Data includes the following kind of information: 
- Traffic source data : Information about where website users originate. This includes information about organic traffic, paid search traffic, and display traffic.
- - Content data : Information about the behavior of 
users on the site. This includes the URLs of pages that users look at, and how they interact with page content.
- Transaction data : Information about the transactions that occur on the Google Merchandise Store website.

A smaller and cleaner version of this data is available on Kaggle: https://www.kaggle.com/competitions/ga-customer-r evenue-prediction/data


