# Decision Tree vs. Naive Bayes Classifier

This repository contains the implementation of two classification models, Decision Tree and Naive Bayes, applied to a car classification problem using the `car_train` and `car_test` datasets. The models' performance is compared, with the Decision Tree achieving an accuracy of 93.8% and the Naive Bayes classifier achieving an accuracy of 79.14%.

## Problem Statement

The goal of this project is to classify cars based on a set of features provided in the dataset. Two machine learning models, Decision Tree and Naive Bayes, were implemented to perform this classification task. The accuracy of both models was evaluated on the `car_test` dataset.

## Implementation Details

The repository is organized as follows:

- `Decision_Trees.ipynb`: A Jupyter Notebook containing the implementation and evaluation of the Decision Tree classifier.
- `Naive_Bayes.ipynb`: A Jupyter Notebook containing the implementation and evaluation of the Naive Bayes classifier.
- `car_train.csv` and `car_test.csv`: Datasets used for training and testing the classification models.

## Decision Tree Classifier

The Decision Tree classifier was implemented to create a decision tree that recursively splits the data based on the feature that provides the best separation. The accuracy of this model was found to be 93.8% on the `car_test` dataset.

## Naive Bayes Classifier

The Naive Bayes classifier was implemented using the Naive Bayes algorithm, which is based on Bayes' theorem. It makes the naive assumption of independence between features. The model achieved an accuracy of 79.14% on the `car_test` dataset.

## Model Comparison

The primary focus of this project is to compare the performance of the Decision Tree and Naive Bayes classifiers. The Decision Tree outperformed Naive Bayes in terms of accuracy, achieving 93.8% accuracy compared to Naive Bayes's 79.14% accuracy.