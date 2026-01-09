# Supervised--mini-project-classification-
Objective: The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.

 # Dataset

The dataset is a locally provided breast cancer dataset (CSV file).

It contains numerical features describing tumor characteristics.

# Target variable:

0 → Malignant

1 → Benign

 Technologies Used

Python

Jupyter Notebook

# Libraries:

NumPy

Pandas

Matplotlib

Scikit-learn

# Data Preprocessing

Missing Value Handling

Checked for missing values.

Missing values (if any) were filled using mean imputation.

Feature Scaling

Applied StandardScaler to normalize features.

Necessary for distance-based models like SVM and k-NN.

# Train-Test Split

Data split into 80% training and 20% testing sets.

 Classification Algorithms Implemented

# Logistic Regression

Suitable for binary classification problems.

# Decision Tree Classifier

Simple and interpretable but prone to overfitting.

# Random Forest Classifier

Ensemble method that improves accuracy and reduces overfitting.

# Support Vector Machine (SVM)

Effective in high-dimensional spaces and complex decision boundaries.

# k-Nearest Neighbors (k-NN)

Classifies based on proximity to neighboring data points.

# Model Evaluation

Models were evaluated using:

Accuracy Score

Classification Report (Precision, Recall, F1-score)

# Performance Summary

Best Performing Models: Support Vector Machine (SVM) and Random Forest

Worst Performing Model: Decision Tree Classifier
