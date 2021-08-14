# Bank-Loan-Payment-Prediction
Illustrates the pattern of loan payment by various customers based on their previous financial history, age, gender, education, terms &amp; principal. Previse whether a customer pays the loan back if sanctioned. 


 
## About DataSet

Source : https://www.kaggle.com/zhijinzhai/loandf

This df set includes customers who have paid off their loans, who have been past due and put into collection without paying back their loan and interests, and who have paid off only after they were put in collection. The financial product is a bullet loan that customers should pay off all of their loan debt in just one time by the end of the term, instead of an installment schedule. Of course, they could pay off earlier than their pay schedule.

## Data Cleaning

Dropped Loan_ID column as it has no importance

## Feature Engineering

The date columns are converted to seperate day, month & hour columns for better pattern recognition


## ML Models Used

CatBoostClassifier,
Logistic Regression,
Support Vector Machine,
Decision Tree,
Neural Network,
Random Forest,
XGBoost,
LGBMClassifier,
XGBRFClassifier,
GradientBoosting,
GaussianNB,
KNeighborsClassifier.

# Results-

![Untitled](https://user-images.githubusercontent.com/85584749/129441516-1feafbf3-7e84-4f48-9db7-c4d68e34a8e0.png)

## Sorted BarPlot of Accuracy

![Untitled](https://user-images.githubusercontent.com/85584749/129441458-ad114d52-5849-45a3-87a3-c6f5be8fdffa.png)
