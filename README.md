# titanic
Highest accuracy we got using KNNClassification with neighbors = 5 and weights = 'distance' is 97.79%

KNN- from sklearn.neighbors import KNNClassifier

In Decision Tree Classification, when criterion ='gini', our model is 98% accurate.

DT- from sklearn.tree import DecisionTreeClassifier

Logistic Regression has 80% accuracy with C=1e4 and we're fitting it.

LogReg - from sklearn.linear_model import LogisiticRegression

Using Gradient Boosting with learning_rate = 0.3, our model is 95% accurate.

Before using GradientBoosting we have to import the modeule xgboost

import xgboost

then implement GradientBoosting present in sklearn.ensemble

Gradient Boosting- from sklearn.ensemble import GradientBoostingClassifier

