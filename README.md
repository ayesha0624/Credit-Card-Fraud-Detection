# Credit-card-fraud-detection
## Problem Statement
The problem that i am going to solve is to understand the features and gather insights to identify the fraud transactions. 

## Data scource
Used data from Kaggle (Machine Learning Group - ULB : https://www.kaggle.com/mlg-ulb/creditcardfraud)
## Data Description
This dataset contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, we cannot provide the original features and more background information about the data. 
Features __V1, V2, … V28__ are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature __'Time'__ contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature __'Amount'__ is the transaction Amount. Feature __'Class'__ is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Conclusion:

__Logistic regression__ performs well in classifying fraud transactions with excellent __recall score of 0.955.__
__Random Forest__ performs well on classifying frauds and normal transactions which gives higher __F1 score of 0.814__ compared to other models.

![](https://github.com/Dheepak-97/Credit-card-fraud-detection/blob/master/final%20result.png)

















