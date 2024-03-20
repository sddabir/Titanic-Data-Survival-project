# Titanic-Data-Survival-project


# Overview

This project focuses on analyzing the Titanic dataset, which contains information about passengers aboard the Titanic, including whether they survived or not. The primary goal is to build a classifier to predict survival based on various attributes such as age, sex, passenger class, and others.

# Dataset

You can obtain the Titanic dataset from Kaggle or download it directly from here. After downloading, unzip the tarball to get two CSV files: train.csv and test.csv. These files contain the training and test data, respectively. You can load them into your Python environment using pandas' read_csv() function.

# Objective

The main objective of this project is to train a classifier that can predict the Survived column (whether a passenger survived or not) based on the other columns in the dataset. This involves preprocessing the data, selecting appropriate features, training various machine learning models, and evaluating their performance.

# Steps

Data Loading: Load the training and test data from the CSV files using pandas.

Data Preprocessing: Clean the data by handling missing values, encoding categorical variables, and scaling numerical features. This involves creating separate pipelines for numerical and categorical data and joining them using a ColumnTransformer.

Model Training: Train different classifiers such as RandomForestClassifier and SVC using the preprocessed data. Evaluate their performance using cross-validation and select the best-performing model.

Model Evaluation: Evaluate the chosen model on the test data to assess its generalization performance.

Analysis: Conduct further analysis to gain insights from the data. For example, calculate the mean survival rate based on age groups and the number of relatives on board.

# Libraries Used
pandas: For data manipulation and loading CSV files.

scikit-learn: For building machine learning models, preprocessing data, and evaluating model performance.

Ensure these libraries are installed in your Python environment to run the project successfully.

# Files Included
train.csv: Training data containing information about passengers.

test.csv: Test data for evaluating the trained model.

Titanic Data Project.ipynb: Jupyter Notebook containing the code for data analysis, model training, and evaluation.
