# Iris_Flowers_Classification

## Goal

The purpose of this project is to build a machine learning classification system from start to finish.
The goal of the model is to classify the type of iris flower based on four features: sepal length, sepal width,
petal length, petal width.

## Approach

First, imported the data using Panda's read_csv. Then I summarized and visualized the data using multivariate and
univariate graphs. After that, I divided the dataset into train/test splits using sklearn. I used cross validation to evaluate
6 different models: logistic regression, linear discriminant analysis, K neighbors classifier, decision tree classifier, Gaussian naive bayes, support vector machine, and found that support vector machine has the best performance. Then, I trained a SVC model on the training
set and made predictions based on the validation set. I evaluated the results using accuracy score, confusion matrix, precision,
recall, f1-score, and support.

## Language + Libraries Used

Python | Libraries: pandas, sklearn, matplotlib

## Credit

Dataset from [UC Irvine](https://archive.ics.uci.edu/dataset/53/iris)
Based on this [tutorial](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)

## Results

Accuracy: 0.9666666666666667

Classification report and confusion matrix in the Jupyter Notebook.
