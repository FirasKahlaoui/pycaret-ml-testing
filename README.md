# PyCaret Testing

This repository contains experiments and demonstrations of PyCaret, a low-code machine learning library in Python. PyCaret simplifies the process of training, comparing, and tuning machine learning models.

## Prerequisites

Make sure you have one of the following Python versions installed:

- Python 3.9  
- Python 3.10  
- Python 3.11  

> **Note**: PyCaret **only** supports these Python versions.

## Installation

To install PyCaret, use the following command:

```bash
pip install pycaret
```

## Usage

Run the provided Jupyter notebooks or Python scripts to see PyCaret in action for tasks such as classification, regression, and clustering.

## Plot Types in PyCaret Model Evaluation

When you run the `evaluate_model(model)` function in PyCaret, it allows you to visualize a variety of diagnostic plots to better understand your machine learning model's performance. Here’s a brief explanation of each plot type:

- **Pipeline Plot**: Shows the steps of the preprocessing pipeline applied to the data before training the model.
- **Hyperparameters**: Displays the hyperparameters of the trained model.
- **AUC (Area Under the Curve)**: Plots the ROC curve and calculates the AUC score, which helps evaluate the model’s performance in binary classification.
- **Confusion Matrix**: A table used to describe the performance of a classification model by showing the counts of true positive, true negative, false positive, and false negative predictions.
- **Threshold**: Shows the probability threshold for classifying positive and negative classes.
- **Precision-Recall**: Plots precision vs. recall, useful when you need a balance between both metrics.
- **Prediction Error**: Visualizes the difference between the predicted and actual values for regression tasks.
- **Class Report**: Generates a detailed classification report with metrics like precision, recall, F1-score, and accuracy.
- **Feature Selection**: Highlights the most important features contributing to the model's predictions.
- **Feature Importance**: Ranks features based on their importance to the model.
- **Learning Curve**: Shows how the model performance changes with varying amounts of training data.
- **Manifold Learning**: Visualizes high-dimensional data using dimensionality reduction techniques like t-SNE or UMAP.
- **Calibration Curve**: Plots the probability calibration of the classifier.
- **Validation Curve**: Plots training and validation scores to help understand model overfitting or underfitting.
- **Dimensions**: Plots a two-dimensional scatter plot of data points after dimensionality reduction.
- **KS Statistic Plot**: Shows the Kolmogorov-Smirnov (KS) statistic to compare the model's predicted probabilities to actual outcomes.
- **Lift Chart**: Visualizes the lift of the model over random guessing.
- **Gain Chart**: Shows how well the model improves upon random guessing in terms of cumulative gains.
- **Decision Tree**: Visualizes a decision tree model.
- **Decision Boundary**: Shows how the model separates classes by plotting the decision boundary.

