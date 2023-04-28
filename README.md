Space-x project

  Space-x is a learning project in data science.It includes different parts which data scientists usually encounter in real projects such as data gathering, data   preparation and feature engineering, machine learning models and visualization. In addition, the different parts of python syntax and working with various libraries are exhibited.
  
Space-x project objective

We want to predict whether or not a rocket launched before is able to land successfully? If it could land successfully, it would be able to reuse. We use machine learning techniques to answer this question.

This project consist of 5 stages:

1. Importing required libraries and objects
2. Gaining insight into dataset
3. Data preparation
4. Preparing and using machine learning methods
5. exporting the best model according to results to deploy and use it later

Stage 1

following libraries are used in this notebook
 1. Pandas 
 2. Matplotlib
 3. Seaborn
 4. Sklearn
 
Stage 2

In this stage the dataset is read with pandas and some python methods are used to explore the data. In addition, with the help of seaborn, some plots are drawn to gain deeper insight into the data.

Stage 3

In this step, the data is manipulated to prepare the data frame for machine learning. This includes:
  1. Working with missing values
  2. Dropping unneeded columns
  3. Modify some columns by splitting them
  4. Converting categorical variables to numeric ones by dummy method
  5. Standardizing the independent variables by Scikit learn library
  6. Saving the final data frame with pandas

Stage 4
Four classification machine learning models including: 
  1. Logistic Regression
  2. Support Vector Machine
  3. Decision Tree Classification
  4. K Nearest Neighbors
  
  Will be trained and tested. Then, their results such as the confusion matrix and ROC curve are applied  to evaluate the models and finally the most appropriate model is chosen

Stage 5

With pickle library the best mode is saved in PKL format to use in deploying stage and use it later by stakeholders


