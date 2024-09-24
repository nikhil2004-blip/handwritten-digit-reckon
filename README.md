# Handwritten Digit Recognition with Random Forest

This project demonstrates how to build a machine learning model to recognize handwritten digits using the `scikit-learn` library. The dataset used is the classic "Digits" dataset, which is pre-loaded in `scikit-learn`. The model is trained using a Random Forest Classifier.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Results](#results)

## Overview
The goal of this project is to recognize handwritten digits (0 to 9) using a Random Forest Classifier. The model is trained and evaluated on the `Digits` dataset, achieving high accuracy.

## Dataset
The `Digits` dataset consists of 8x8 grayscale images representing handwritten digits. It contains a total of 1,797 samples, each labeled from 0 to 9.

## Installation
To run this code, you need to have the following libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## Results
           precision    recall  f1-score   support

           0       0.98      1.00      0.99        58
           1       0.95      0.98      0.96        55
           2       1.00      0.98      0.99        54
           3       0.96      0.96      0.96        52
           4       1.00      1.00      1.00        55
           5       0.98      0.96      0.97        50
           6       1.00      0.98      0.99        60
           7       0.96      1.00      0.98        50
           8       0.96      0.89      0.92        54
           9       0.94      0.98      0.96        52

        accuracy                           0.97       540
       macro avg       0.97      0.97      0.97       540
    weighted avg       0.97      0.97      0.97       540



You can install these libraries using pip:
```bash
pip install numpy pandas matplotlib scikit-learn
