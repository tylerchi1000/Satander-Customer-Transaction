# Santander Customer Transaction Kaggle Competition

This is a repository for the Santander Customer Transaction Kaggle Competition. The goal of this competition is to predict whether a customer will make a transaction or not based on anonymized features.

## Data

The data for this competition can be found on the Kaggle website. The dataset contains a training set of 200,000 examples and a test set of 200,000 examples. Each example has 200 features and a binary target variable indicating whether a transaction was made or not.

## Satander Customer Transaction Notebook

The Satander_Customer_Transaction_Notebook.ipynb notebook contains both the exploratory data analysis (EDA) and the TensorFlow model for this project. In this notebook, we explore the distribution of features and the relationship between features and the target variable. We also apply a data preparation pipeline that applies a series of transformations to the data, including scaling and dimensionality reduction. The resulting transformed data is then fed into a TensorFlow model, which consists of several dense layers with dropout regularization. The model is trained on the training set and evaluated on the test set. The performance of the model is measured using the ROC-AUC score.
Usage

To use this repository, you can follow these steps:

    Download the dataset from the Kaggle website and place it in the data directory.
    Run the Satander_Customer_Transaction_Notebook.ipynb notebook to perform exploratory data analysis, prepare the data, and train the TensorFlow model.

## Requirements

To run this repository, you will need:

    Python 3.x
    Jupyter Notebook
    TensorFlow
    Pandas
    NumPy
