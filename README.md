# Financial-Delinquency-Prediction

Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions. For markets and society to function, individuals and companies need access to credit. 

Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. This problem aims to improve on the state of the art technique in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years.

**Project Objective**

Predict probability of each individual having greater than 90 days past due deliquency on their loans.

**Business objective**

Create model that estimates probability of a customer defaulting based on certain features, categorizing them as a high risk or low risk borrower to determine whether to loan money and how much.

**Approach**

1.Preprocess data

2.Analyze dataset

3.Engineer features

4.Build models

5.Evaluate models
 


Historical data are provided on 250,000 borrowers 

**Metric for evaluation= AUC**

**Supervised Binary classification prediction Problem**

**Final model used - Gradient boosting Classifier with GridSearchCV with AUC score of 0.84**


