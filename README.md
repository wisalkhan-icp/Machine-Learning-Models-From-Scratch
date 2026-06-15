# Machine Learning Models From Scratch

Welcome to the **Machine Learning Models From Scratch** repository! This project contains end-to-end implementations of fundamental machine learning algorithms built entirely from scratch using Python and NumPy.

The goal of this repository is to provide a deeper understanding of how machine learning algorithms work internally by implementing the mathematics, optimization procedures, and learning mechanisms without relying on high-level machine learning frameworks.

To validate correctness and performance, each custom implementation is compared against its equivalent implementation in scikit-learn using the same datasets.

---

## Repository Structure

The repository is organized into separate directories, each containing a machine learning algorithm and its corresponding implementation files.

### Regression Models

* **Linear Regression**
* **Multiple Linear Regression**
* **Polynomial Regression**

These models focus on predicting continuous target values using gradient descent and error minimization techniques.

### Classification Models

* **Logistic Regression**
* **Multi-Class Logistic Regression**
* **Naive Bayes**
* **Support Vector Machine (SVM)**
* **K-Nearest Neighbors (KNN)**

These algorithms are designed for binary and multi-class classification tasks.

### Tree-Based Models

* **Decision Tree Classifier**
* **Decision Tree Regressor**
* **Random Forest Classifier**
* **Random Forest Regressor**

These models use recursive splitting, information gain, Gini impurity, and ensemble learning techniques.

### Clustering

* **K-Means Clustering**

An unsupervised learning algorithm used for grouping similar data points.

---

## Key Features

* **Built Completely From Scratch** using Python and NumPy.
* **Minimal Dependencies** with a focus on understanding algorithm internals.
* **Vectorized Implementations** for improved computational efficiency.
* **Object-Oriented Design** following industry-standard APIs such as `.fit()` and `.predict()`.
* **Benchmarking Against Scikit-Learn** to verify correctness and performance.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/wisalkhan-icp/Machine-Learning-Models-From-Scratch.git
cd Machine-Learning-Models-From-Scratch
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Usage Example

The workflow is similar across all implemented models.

```python
from linear_regression import LinearRegression
import numpy as np

# Create model instance
model = LinearRegression(
    learning_rate=0.01,
    iterations=1000
)

# Train model
model.fit(X_train, y_train)

# Generate predictions
predictions = model.predict(X_test)
```

---

## Learning Objectives

This project helps you understand:

* Mathematical foundations of machine learning algorithms.
* Gradient descent optimization.
* Cost and loss functions.
* Classification and regression techniques.
* Ensemble learning methods.
* Vectorized computations using NumPy.
* Performance comparison with production-grade libraries.

---

## Benchmarking

Each custom implementation is evaluated against its corresponding scikit-learn implementation to analyze:

### Accuracy

Verifies that the custom algorithm converges to results comparable to established machine learning libraries.

### Performance

Examines computational efficiency and highlights the optimizations available in production-grade implementations.

### Implementation Understanding

Provides insight into the internal mechanics hidden behind high-level machine learning APIs.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

---

## License

MIT License

Copyright (c) 2026 Wisal Khan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
