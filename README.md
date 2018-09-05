# Red-Wine-Quality
Red Wine Quality
The data set used for this project is obtained from [here](https://www.kaggle.com/piyushgoyal443/red-wine-dataset/downloads/wineQualityReds.csv/1),Created by: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009. the description file [here](https://www.kaggle.com/piyushgoyal443/red-wine-dataset/downloads/wineQualityInfo.txt/1)

### Requirements needed
In order to run this project file, you need;
* Python version 2.7 installed (earliest). 

### Python libraries used

import pandas as pd
import numpy as np
from IPython.display import display
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.svm import SVC
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import confusion_matrix, classification_report
from sklearn.model_selection import train_test_split, cross_val_score, GridSearchCV
from sklearn.model_selection import cross_val_score
from sklearn.metrics import confusion_matrix
from sklearn import model_selection
import warnings; warnings.simplefilter('ignore')
%matplotlib inline


### Files Description
This repository contains the following files:

* WineQualityInfo.txt: this contains the description of the data set used.
RedWineQuality.ipynb: this notebook file contains  markdown of cells and code cells used in realizing this projects, details are found here.
* RedWineQuality.html: The html verion of same notebook
* wineQualityReds.csv: This tidy data set contains 1,599 red wines with 11 variables on the chemical properties of the wine. At least 3 wine experts rated the quality of each wine, providing a rating between 0 (very bad) and 10 (very excellent).
* README.md: This file contains a brief summary.

To complete the project, CRISP-DM has been used. The different processes are as below.

> Business understanding
> Data Understanding
> Preparing Data
> Analysis/Modeling
> Validation
> [Deployment](https://medium.com/@jamal.henani/red-wine-quality-947e3e3c275b)

## Project Motivation
Obviously there’s a lot that goes into making great wines. If there were a way to track the world’s most popular drink, wine would certainly be right up there on the list. I'm curious about the factt that wine is so popular, but yet defining its quality is so complicated, even with the chemical components of red wine. As if that is not all, consumers have diverse views on the issue of high quality wine. This has left me with no choice than asking a few business questions, which are answerable using the red wine data set.
- How do the acidity and quantity of chlorides affect red wine quality
- Which is of high quality? Low alcoholic red wines or high alcoholic red wines?
- How accurate is it to determine the quality of red wine from its chemical components?

## Findings:
While quality of red wine is very important and should be considered both by the companies or consumers, we have how ever discover that;
* More acid and less chlorides are needed for high quality red wines.
* A highly alcoholic wine means high quality.
* It’s possible to determine the red quality from it’s chemical constituents, but only with 74% accuracy

## Licensing, Authors, Acknowledgements
- credits to give Kaggle for the data set.
 - My acknowledgement to Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009 for compiling the dataset..

## Useful Links
https://stackoverflow.com/questions/35948995/seaborn-lmplot-got-an-unexpected-keyword-argument-figsize
https://seaborn.pydata.org/generated/seaborn.regplot.html
https://machinelearningmastery.com/logistic-regression-for-machine-learning/
http://scikit-learn.org/stable/modules/svm.html
