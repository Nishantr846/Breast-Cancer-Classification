# Breast Cancer Prediction using Logistic Regression

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Setup and Usage](#setup-and-usage)
  - [Clone the Repository](#1-clone-the-repository)
  - [Install Dependencies](#2-install-dependencies)
  - [Run the Script](#3-run-the-script)
  - [Test the Predictive System](#4-test-the-predictive-system)
- [Model Evaluation](#model-evaluation)
- [License](#license)

---

## Overview
This project uses logistic regression to classify breast cancer as malignant or benign based on a set of features from the **Breast Cancer Wisconsin Dataset**. The model is trained and evaluated using `scikit-learn`.

---

## Features
- Implements logistic regression for binary classification.
- Uses the Breast Cancer Wisconsin dataset from `scikit-learn`.
- Includes a predictive system to classify new data points.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - `numpy`
  - `pandas`
  - `scikit-learn`

---

## Dataset
The dataset is loaded directly from `scikit-learn`. It includes 30 numeric features, such as mean radius, mean texture, and mean smoothness, along with a target variable (`label`), where:
- `0` represents malignant tumors.
- `1` represents benign tumors.
