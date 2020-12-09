# Project proposal for *Classification Model Experiments For Credit Card Dataset*
Author: *ALAN JOSEPH*

## 1. Why: Question/Topic being investigated 2pts

I would like to understand which SK-learn classifier works best on the credit card default dataset from the UCI library.


## 2. How: Plan of attack 2pts

I will download the dataset available on the UCI website and then use the lab 3 notebook as a template to do this project. The notebook has various classifiers such as LogisticRegression, RandomForestClassifier, GradientBoostingClassifier, etc. My goal will be to identify the best model for prediction. Some features in the dataset are categorical such as education and some are Numerical such as Age and Bill Amount. For encoding I may use one hot encoding. Modifications to the notebook will be made as I see fit to ensure I achieve desired results. 
If time permits I may go further to find a better threshold based on my model and try to explore the implications of false positives or false negatives results.


## 3. What: Dataset, models, framework, components 2pts

Dataset- The credit dataset contains information on payments, demographics, bill statements of credit card clients, etc in Taiwan from April 2005 to September 2005 that was used to predict loan repayment outcomes.

Dataset URL-https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

Scikit-learn Classifiers- LogisticRegression, RandomForestClassifier, GradientBoostingClassifier