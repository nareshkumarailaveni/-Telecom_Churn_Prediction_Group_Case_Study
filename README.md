# Telecom Churn Prediction Group Case Study
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.

## Table of Contents
* Data Understanding, Preparation, and Pre-Processing/Feature Engineering and Variable Transformation/Exploratory Data Analysis/Model Selection, Model /Building, and  Prediction/Conclusion/Identifying the  churn indicators using Logistic Regression model for bussiness problemEvaluation/Calculating R-squared score on test data
* Numpy,Pandas, Matplotlib, Seaborn and Sklearn libraries used
* Conclusions
* Course Lectures

## General Information
The main objective of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.

It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.

Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.

Recommend strategies to manage customer churn based on your observations.

Note that it's highly likely that you'll need to build multiple models to fulfil the objectives mentioned in Points 1 and 2. Since here, you have a large number of attributes, and thus you should try using a dimensionality reduction technique such as PCA and then build a predictive model. After PCA, you can use any classification model.

The above model will only be able to achieve one of the two goals - to predict customers who will churn. You can’t use the above model to identify the important features for churn. That’s because PCA usually creates components that are not easy to interpret.

Therefore, build another model with the main objective of identifying important predictor attributes which help the business understand indicators of churn. A good choice to identify important variables is a logistic regression model or a model from the tree family. 

## Conclusions

Recall this is a classification problem with classes 0 and 1. It is noticed that the coefficients are both positive and negative. The positive scores indicate a feature that predicts class 1 i.e., customer will churn, whereas the negative scores indicate a feature that predicts class 0 i.e., customer don't churn.

* Telecom company needs to pay attention to the monthly 2g/3g data rates and roaming rates. They need to provide good offers to the customers who are using services from a data and roaming zone.

* The company needs to focus on the Operator T2F, T2M and T2C local and STD rates. Also, focus should be on addressing the special outgoing and ISD incoming call rates. Need to provide some kind of packages for customers using services of special outgoing and ISD incoming calls.

* Inaddition, with increase in number of last mobile recharges from june, july and august months, the chance of customer churning is increasing. Company should focuss on these customers as it can be considered as the potential risk of churning. The telecom company should collects customer query and complaint data and work on their services according to the needs of customers. 
  
## Technologies Used
* numpy - version 1.23.5
* pandas - version 1.5.4
* Seaborn - version 0.12.2
* Matplotlib - version 3.7.1
* Python - version 3

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on this tutorial.


## Contact
Created by [ailaveninareshkumarailaveni@gmail.com] - feel free to contact me @+91-9972423009.
