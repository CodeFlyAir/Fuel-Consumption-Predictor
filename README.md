# Fuel-Consumption-Predictor
![image](https://user-images.githubusercontent.com/95049059/183258611-558f7904-4278-4f03-8816-b6c0995cc3a2.png)


## What is the project about ?
This machine learning project is build on a dataset consisting of 8 different parameters consisting of :
1. MPG (Miles per Gallon)
2. Cylinders
3. Displacement
4. Horsepower
5. Weight
6. Acceleration
7. Model year
8. Origin
9. Car Name

Based on these parameters the model predicts the Fuel Consumption (Miles per Gallon) of a car.

## Insight :
Some important insights observed from the dataset are :
- There are missing cells
- There are no duplicate rows
- MPG is highly correlated with : i) Cylinder ii) Weight iii) Displacement iv) Model Year v) Origin
- Horsepower and Car Name as high cardinality
- Cylinders , Origin, Brand, Model has categorical values

## Tools Used :
- Pandas
- Numpy
- Seaborn
- Matplotlib
- StandardScaler
- OneHotEncoder
- RandomizedSearchCV

## Principles Used :
1. Standard Scaling method is used to scale the numeric features to a same level.
2. One Hot Encoding is used to encode the categorical features.
3. Polynomial Features 

## Algorithms Used :
- Linear Regression
- Bayesian Ridge Regression
- Ridge Regression
- Lasso Regression
- XGBoost Regressor
- Elastic Net
- Random Forest Regressor
- Support Vector Regressor
- KNN Regressor

## Algorithm Chosen for Final Modelling :
Bayesian Ridge Regression

## Citations :
Pseudo-APA format
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

BiBTeX citation
format
@misc{Dua:2019 ,
author = "Dua, Dheeru and Graff, Casey",
year = "2017",
title = "{UCI} Machine Learning Repository",
url = "http://archive.ics.uci.edu/ml",
institution = "University of California, Irvine, School of Information and Computer Sciences" }

