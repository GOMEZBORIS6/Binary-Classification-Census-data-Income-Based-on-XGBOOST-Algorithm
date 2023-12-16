# Binary-Classification-Census-data-Income-Based-on-XGBOOST-Algorithm

## Using the XGBoost algorithm
The aim of this project is to describe how the **XGBoost** (extreme gradient boosting) algorithm works and to
test its implementation in Python based on an example dataset.

This project involves conducting independent research. In the process, we will ask ourselves the following three questions:
  - For what type of machine learning task is this method useful (supervised versus unsupervised, classification
or regression)?
  - How does the algorithm work?
  - Are there any applications of this method to economic or social science data?

To perform this project we need to apply XGBoost algorithm on dataset. We therefore select a dataset to be used, namely the **Income Census** dataset, which has been extracted from the OECD Income Database [machine learning repository (UCI)](https://archive.ics.uci.edu/dataset/20/census+income), which contains about 32561 rows and 15 columns. The target variable in the data set is income level, which shows whether a person earns more than 50,000 per year or not, based on 14 features containing information on age, education, education-num, gender, native-country, marital status, final weight, occupation, work classification, gender, race, hours-per-week, capital loss, and capital gain.

So, the target variable (income) will be represented by binary classes. the class 0 for people having income less than or equal to 50k $ per year (<=50k $), and the class 1 for people having income more than 50k $ per year (>50k $).

## Task's description
The prediction task is to determine whether a person makes over $50K a year (income exceeds $50K/yr) based on census data. Also known as "Adult" dataset.

## Result
After cleaning and preparing the data for the models, we perform the **XGBoost** algorithm in the dataset.
For achieving high results in terms of evaluation metrics. A **84,98%** accuracy score.
