# Naive Bayes Classifier on Iris Dataset

This repository demonstrates the implementation of a **Naive Bayes classifier** on the **Iris dataset**, a well-known dataset commonly used in machine learning and statistics. The Iris dataset contains 150 instances of iris flowers, classified into three species: **Setosa**, **Versicolor**, and **Virginica**. Each flower is described by four features: **sepal length**, **sepal width**, **petal length**, and **petal width**.

## Project Overview

The goal of this project is to use a **Naive Bayes classifier** to predict the species of an iris flower based on its features. Naive Bayes is a probabilistic classifier based on **Bayes' Theorem**, which assumes the features are conditionally independent given the class. Despite this assumption, Naive Bayes performs well in many practical classification tasks, especially with datasets like Iris.

## Features

- **Data Preprocessing**: The project includes steps for loading, exploring, and visualizing the dataset. It handles necessary preprocessing such as feature scaling (if required).
- **Model Implementation**: The classifier is built using **GaussianNB** from scikit-learn, which assumes the features follow a Gaussian distribution (common for continuous data like the Iris dataset).
- **Model Evaluation**: The model's performance is evaluated using metrics like accuracy, confusion matrix, precision, recall, and F1-score.
- **Visualization**: Various plots are used to visualize data distributions, feature relationships, and decision boundaries of the Naive Bayes classifier.

## Requirements

- Python 3.x
- Libraries: 
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

You can install the required libraries using `pip`:

```bash
pip install -r requirements.txt
