# CS 6220 - Homework 1: Iris Classification Pipeline

This project builds a scikit-learn pipeline to classify Iris flower species 
based on sepal and petal measurements, as part of CS 6220 Homework 1.

## Overview

- Loads the classic Iris dataset (via `sklearn.datasets.load_iris`)
- Splits data into 80% training / 20% test sets
- Builds a pipeline with `StandardScaler` + `LogisticRegression`
- Trains and evaluates the model, reporting accuracy, training time, and testing time
- Visualizes the data with a sepal length vs. width scatterplot

## Results

- **Accuracy:** 1.0000 (100%)
- **Training time:** ~0.0056 seconds
- **Testing time:** ~0.0022 seconds

## Requirements

- Python 3.x
- Jupyter Lab
- Dependencies listed in `requirements.txt`

## Setup and Execution

1. Clone this repository:
