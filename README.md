# Unsupervised Machine Learning Project: Online Encyclopedia of Integer Sequences (OEIS).

Logistic regression, AdaBoost and XGBoost classifiers are used to determine whether a sequence increases or decreases at the 10th value from the 9th value with the previous nine sequence values used as features. Data is retrieved from the Online Encyclopedia of Integer Sequences (OEIS). 

The data files are located in the "Data" folder with only oeisvals.csv used in the code but oeisnames.csv is also provided as a reference to provide context to the integer sequences. The ipynb file is self-contained and downloads the data from a public Google Drive folder. Alternatively the data can be downloaded at this link https://davidbieber.com/snippets/2020-06-28-oeis-download/.

Beyond optimizing model performance, the focus of this work is on the impact of outliers and determining if reduced data sets can generalize well out of distribution for the various classifiers. Threshold moving is also discussed in the context of logistic regression and a range of classification metrics are used beyond accuracy (F1, AUC). 
