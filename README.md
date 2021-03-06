# US-Income challenge 
In this assignment we are given 2 datasets. one for training and on for testing. The goal is to predict income of us-citizens based 14 features. 

First we measure baseline accuracy using random forrest. 

after this we'll try to improve the score by tuning hyperparameters and try to compensate for overfitting.


## baseline accuracy 
| Classifier model  | Accuracy score      | Set type | Random state | 
|------------------------|:----------------:|:-----:|:--------------:|
| RandomForrestClassifier | 99,99%  | train | 30 | 
| RandomForestClassifier | 85,14% | test  | 30 |


![](visuals/cf_baseline.png)

![](visuals/f1.png)

![](visuals/roc_score.png)


as you can see traing score is very high but drops when given unseen data. this is a clear sign of overfitting. In the confusion matrix below we see a lot of data is misclassified as false negatieve.

### cross-validation

cross validation was my first attempt at getting a better score. I fitted the traing set and got a lower accuracy score. This combets overfitting 

|cross validation score | number of folds  | standard deviation |
|-----------------------|------------------|--------------------|
|   85.72%              |        10        |     +/- 0.45       |

## Mission objectives

- Be able to analyze a machine learning problem
- Be able to reason about possible causes of overfitting
- Be able to remedy the causes of overfitting
- Be able to tune parameters of a machine learning model
- Be able to write clean and documented code.


## conclusion
I kept seperating features and refitting to get a better score. The dataset is inbalenced from the beginning. Even if i rebalence and keep looking for better features i can't get the score higher than an extra 2%. using more trees and optimising the model gives deminishing returns after severel folds. 



## Contributors
| Name                  | Github                                 |
|-----------------------|----------------------------------------|
| Quinten Wildemeersch          | https://github.com/QuintenMM   |
