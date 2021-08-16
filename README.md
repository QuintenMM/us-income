# US-Income challenge 
In this assignment we are given 2 datasets. one for training and on for testing. The goal is to predict income of us-citizens based 14 features. 

First we measure baseline accuracy using random forrest. 

after this we'll try to improve the score by tuning hyperparameters and try to compensate for overfitting.


## baseline accuracy 
| Classifier model  | Accuracy score      | Set type | Random state | 
|------------------------|:----------------:|:-----:|:--------------:|
| RandomForrestClassifier | 99,99%  | train | 30 | 
| RandomForestClassifier | 85,14% | test  | 30 |

as you can see traing score is very high but drops when given unseen data. this is a clear sign of overfitting. In the confusion matrix below we see a lot of data is misclassified as false negatieve.

## Mission objectives

- Be able to analyze a machine learning problem
- Be able to reason about possible causes of overfitting
- Be able to remedy the causes of overfitting
- Be able to tune parameters of a machine learning model
- Be able to write clean and documented code.






## Contributors
| Name                  | Github                                 |
|-----------------------|----------------------------------------|
| Quinten Wildemeersch          | https://github.com/QuintenMM   |
