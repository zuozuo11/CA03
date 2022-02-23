# CA03



## Background

The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. We want to through decision tree model to forcast a perple's revernue.

---------------------------------------------------------------------------------------

## install
We will use following packages:


import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn import metrics
from category_encoders import OrdinalEncoder
from sklearn.tree import export_graphviz
from six import StringIO  
from IPython.display import Image  
import pydotplus
import graphviz
import os
from sklearn.metrics import confusion_matrix
from sklearn.metrics import classification_report
from sklearn.metrics import roc_curve, auc
from sklearn.model_selection import GridSearchCV
from sklearn.tree import DecisionTreeRegressor
from sklearn import metrics

---------------------------------------------------------
## process

1. Data Quality Analysis (DQA)
2. Exploratory Data Analysis (EDA)
3. Build Decision Tree Classifier Models
4. Visualize Your Decision Tree using GraphViz
5. Evaluate Decision Tree Performance
6. Tune Decision Tree Performance
7. Conclusion
8. Automation of Performance Tuning
9. Prediction using your “trained” Decision Tree Model
------------------------------------------------------------------

## result

The accuracy of model is 0.841.
