# Udacity-Starbucks-Capstone-Project

The intention of this project is that we apply all the things we learned during the course and demonstrate the process of analyzing and deploying our findings.

## Blogpost
https://kaique-c-oliveira.medium.com/applying-data-science-to-predict-customer-engagement-9c7cdba402f4

## Project Structure
~~~
Notebook {
  Starbucks_Capstone_notebook.ipynb
}
~~~

## Data Origin
All the data used was provided by [Udacity](https://www.udacity.com/)

## Libs

import pandas as pd <br>
import numpy as np<br>
import math<br>
import json<br>
import matplotlib.pyplot as plt<br>
import seaborn as sns<br>
from pandas.io.json import json_normalize<br>
from sklearn.preprocessing import MultiLabelBinarizer<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.preprocessing import MinMaxScaler<br>
from sklearn.ensemble import AdaBoostClassifier<br>
from sklearn.ensemble import GradientBoostingClassifier<br>
from sklearn.ensemble import ExtraTreesClassifier<br>
from sklearn.ensemble import RandomForestClassifier<br>
from sklearn.metrics import classification_report<br>
from sklearn.metrics import confusion_matrix<br>
