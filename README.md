# Name of Project

ML_CA03_Decision Tree


# Project Overview

The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. The following is a description of our dataset:
• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
• Number of attributes (Columns): 7
• Number of instances (Rows): 48,842


# Please download two data files first

1. Census dataset: https://drive.google.com/file/d/1rsQXXHqxeM8bB002RN30oXGBljbNBjow/view?usp=sharing
2. auto_dataset：https://drive.google.com/file/d/1EJfUrO9umOl8D-bN-Y3FReHlgwc8e7w9/view?usp=sharing


# Open colab:
https://colab.research.google.com/drive/1N4Qjaik8m8yrZYxANFZfhl1yY1unavbI?usp=sharing

# Import packages list below:

```bash
#Import packages
import pandas as pd
import numpy as np
#Import visualization package
import matplotlib.pyplot as plt
from sklearn.externals.six import StringIO
from IPython.display import Image
from sklearn.tree import export_graphviz
import pydotplus
#label encoding package
from sklearn.preprocessing import LabelEncoder
#Sklearn packages
from sklearn.metrics import confusion_matrix, classification_report
from sklearn.metrics import roc_curve
from sklearn.metrics import auc
from sklearn.metrics import roc_auc_score
from sklearn.metrics import accuracy_score
from sklearn.metrics import precision_score
from sklearn.metrics import f1_score
from sklearn.metrics import recall_score
```


# Installation

- Mounted the google drive to make files readable: drive.mount('/content/drive/')
- Enjoy the code


# Contact info

Name: Mandy He
Email: she3@lion.lmu.edu

