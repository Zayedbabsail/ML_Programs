# Machine Learning Models Repository

## Overview
This repository contains a collection of machine learning models, categorized into **Supervised**, **Unsupervised**, and **Ensembling** techniques. It also includes necessary datasets for running the models.

### Repository Structure
- **Supervised**: Contains models for supervised learning.
- **Unsupervised**: Contains models for unsupervised learning.
- **Ensembling**: Contains ensemble learning techniques.
- **Datasets**: Contains the datasets required to run the models.

## Folders

### 1. Supervised
This folder contains machine learning models for supervised learning tasks:
- **Decision Tree** (`decision_tree.py`)
- **Logistic Regression** (`logistic_regression.py`)
- **Naive Bayes** (`naive_bayes.py`)
- **Support Vector Machine (SVM)** (`svm.py`)

Each model solves classification problems and is implemented using Scikit-learn, handling both categorical and continuous data.

### 2. Unsupervised
This folder contains unsupervised learning algorithms:
- **K-Means Clustering** (`kmeans.py`): Used for partitioning a dataset into K distinct, non-overlapping clusters.
- **Hierarchical Clustering** (`hierarchical.py`): Clusters data by constructing a hierarchy based on the distance between data points.

These models are designed for tasks like grouping data without predefined labels.

### 3. Ensembling
This folder includes ensemble learning techniques that combine multiple models to improve performance:
- **Random Forest** (`random_forest.py`): An ensemble of decision trees to improve classification accuracy.
- **Bagging** (`bagging.py`): Bootstrap aggregating to reduce variance and avoid overfitting.
- **Boosting** (`boosting.py`): Combines weak learners to form a strong classifier by minimizing errors.

### 4. Datasets
This folder contains all the datasets required to run the programs mentioned in the repository. Each dataset is a CSV file, and the scripts are configured to read data from this directory.

