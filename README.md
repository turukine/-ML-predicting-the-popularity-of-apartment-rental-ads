Project Goal
Master the fundamentals of machine learning and data analysis by building a model to predict the popularity of apartment rental listings.

Basic Concepts
What is Machine Learning?
Methods for automatically discovering patterns in data and using these patterns for prediction.

Types of ML Tasks:
Supervised Learning - has input data (X) and correct answers (y)

Classification - predicting categories (e.g., disease presence)

Regression - predicting numerical values (e.g., prices)

Unsupervised Learning - only input data without answers

Clustering - grouping data

Association - finding relationships between data

Dimensionality Reduction - simplifying data

Practical Task
1. Introduction
Provide 5 examples of ML applications in real life

Classify tasks from the theory section

Explain the difference between multiclass and multilabel classification

Determine the type of house price prediction task

2. Data Analysis
Required libraries:

python
import pandas as pd
import numpy as np
import sklearn
import matplotlib.pyplot as plt
import seaborn as sns
Steps:

Load data from Kaggle (train.json)

Analyze data size, check for missing values

Select columns: 'bathrooms', 'bedrooms', 'interest_level', 'price'

Study the distribution of the target variable (price)

Remove outliers (1st-99th percentiles)

3. Statistical Analysis
Build histograms and boxplots for the target variable

Analyze outliers

Study feature distributions

Build correlation matrices

4. Feature Engineering
Add polynomial features (PolynomialFeatures)

Split data into training and test sets

5. Model Training
Train and compare three models:

Linear Regression

Decision Tree (random_state=21)

Naive models (predicting using mean and median)

Quality metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Square Error)

Result
Compare models using MAE and RMSE metrics on training and test sets, determine the best model.

Additional
Experiment with creating new features and using all available data.
