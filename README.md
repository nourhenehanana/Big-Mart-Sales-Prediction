# Big-Mart-Sales-Prediction
The data scientists at BigMart have collected sales data for 1559 products accross ten stores in different cities. 
Furthermore, certain attributes of each product and store have been defined.
The aim is to build a predictive model and find the sales figures of each product at a particular store.
Using this model, Big Mart will try to understand the properties of products and stores which play a key role in increasing sales. 
The factors that could affect the target variable sales: 

1/ Time of the week: weekends are usually busier and lead to more sales. 

2/ Time of the day: In bigmart the sales are higher in the morning and late evening

3/ Time of the year: Sales are often higher during the last few months of the year

4/ Store size and location

5/ The item being sold 

# the steps we took in this demo: 
1/ made a hypothesis  about the data without looking at it

2/ Moved on to data exploration and found some nuances in the data which recquired remediation

3/ Performed data cleaning and feature engineering and imputed the missing values and solved other irregularities

4/Made new features and also made the data model_friendly unsing one-hot encoding

5/built the regression model

# Some notes for data cleaning and tranformation 

LabelEncoder: 
Encode target labels with value between 0 and n_classes-1. This transformer should be used to encode target values, i.e. y, and not the input X.

Outiliers: 
An outlier is a data point that lies outside the overall patternin a distribution 
A commonly used rule states that a data point is an outlier if is more than 1.5*IQR above the third quartile or below the first quartile. Using this, one can remove the outliers and output the resulting data in fill data variable

Why do we create dummies?
Dummy variables are useful because they allow us to include categorical variables in our analysis, which would otherwise be difficult to include due to their non-numeric nature. They can also help us to control for confounding factors and improve the validity of our results.
