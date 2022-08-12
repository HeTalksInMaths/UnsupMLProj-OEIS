# Supervised Machine Learning Project: Online Encylopedia of Integer Sequences (OEIS).

Logistic regression and AdaBoost classifiers are used with hyperparameter tuning to determine whether a sequence increases or decreases at the 10th value from the 9th value. Data retrived from the Online Encyclopedia of Integer Sequences (OEIS).

The data files are located in the "Data" folder with only oeisvals.csv used in the code but oeisnames.csv is also provided as a reference to provide context to the integer sequences. The ipynb file is self-contained and downloads the data from a public Google Drive folder. Alternatively the data can be downloaded at this link https://davidbieber.com/snippets/2020-06-28-oeis-download/.

Nested cross validation for both hyperparameter tuning and model performance utilized and standard time series data transformations applied. 
