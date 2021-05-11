[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)![Misk Logo](https://i.ibb.co/KmXhJbm/Webp-net-resizeimage-1.png)

---
# Project 2 : Titanic - Machine Learning from Disaster



# Introduction 

## Datasets Description 

The dataset comes from Kaggle competition named ["The Titanic - machine learning from disaster ”](https://www.kaggle.com/c/titanic/data) which was about Titanic that sank in 1912 after hitting an iceberg. The dataset contains two similar datasets that include passenger information like name, age, gender, socio-economic class, the port they embarked from and whether they have relatives with them or not, etc. 
One dataset is titled `train.csv` and the other is titled `test.csv`:
- `train.csv`Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

- The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger.

## Executive Summary
In this project after investigating Titanic dataset and perform visualization approches and applying machine learning models, we found out Random Forest Using Grid Search give us the accurate preduction with score 78%.


## Problem Statment
The project aims to use machine learning models in predicating whether the passengers in the titanic ship survived or not. The problem is a supervised learning problem and since we are tried a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data, it is a classification problem.


# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|PassengerId|int| Train,Test|ID of Passenger| 
|Survived|int| Train,Test|Survival status 0 = No,1 = Yes|
|Pclass|int| Train,Test|Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd|
|Name|str| Train,Test|Name of Passenger|
|Age|float| Train,Test|Age of Passenger|
|SibSp|int| Train,Test|Number of siblings & spouses aboard the Titanic|
|parch|int| Train,Test|Number of parents & children aboard the Titanic|
|Ticket|str| Train,Test|Ticket number|
|Fare|float| Train,Test|Passenger fare|
|Cabin|int| Train,Test|Cabin number|
|Embarked|str| Train,Test|Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton|

