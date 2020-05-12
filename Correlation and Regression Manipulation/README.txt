This folder contains all the data and jupyter notebooks pertaining to regression and correlation between the variables.

The folder named Pairplot descriptions contains our observations of the pairplot constructed in the notebook "Feature on Feature - Correlation." The axies are read from left (1) to right (23) and up (1) to down (23)

The extranious excel files contain different forms of correlation between features and production. The titles describe what is being looked at.

The Jupyter notebooks in this folder (Should be read in this order):

1) Feature on Feature - Correlation
This file will look at all the field features and see if there is any kind of correlations between them. It will do so by constructing a pairplot of all the features.

2) Feature on Feature - Spearman
This file will look at how all the field features correlate with each other using spearman's rank coefficient. We will also being using spearman's to see how the features correlate to both oil and gas production.

3) Feature on Production - Correlation
This file will find the correlation scores of the features on production using three different strategies. We will use LASSO, F-Test, and R^2. It will calculate these correlation scores for all the features on oil and gas production.

4) Using Features to Predict Production
This file will use the features selected in the previous file to see how accurately we can predict production off of those selected features.