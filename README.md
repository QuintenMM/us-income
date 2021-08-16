# US-Income challenge 

Predict the income of a US citizen based. an use model evaluation to check the models.

## Mission objectives

- Be able to analyze a machine learning problem
- Be able to reason about possible causes of overfitting
- Be able to remedy the causes of overfitting
- Be able to tune parameters of a machine learning model
- Be able to write clean and documented code.



## Usage

```python
import pandas
import numpy
import seaborn
import matplotlib.pyplot as plot
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split,cross_val_score,KFold,GridSearchCV
from sklearn.metrics import confusion_matrix,classification_report,accuracy_score
```

## Steps
1. The data is preprocessed already, a training set and a testing set.
3. Fit the Train sets in to the model for a baseline accuracy
4. Tune the hyperparameters of the RandomForestClassifier & Gridsearch to get a better test score and compensate for overfitting.
5. Look for the best parameters and increase score
