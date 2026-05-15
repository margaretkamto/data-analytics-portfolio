# Machine Learning Analysis Project

## Overview

This project was completed for a Machine Learning module. It applies three main machine learning tasks: unsupervised learning, regression, and classification.

The unsupervised learning section uses the METABRIC breast cancer dataset to explore patient grouping patterns. The regression and classification sections use the Bank Marketing dataset to analyse customer call duration and term deposit subscription.

## Coursework Tasks

The project includes three machine learning tasks:

1. Unsupervised learning, using dimensionality reduction and clustering
2. Regression, using a continuous target variable
3. Classification, using a categorical target variable

## Datasets Used

### METABRIC Breast Cancer Dataset

This dataset was used for the unsupervised learning task.

The analysis used selected clinical and mutation-related variables, including age at diagnosis, tumour size, mutation count, positive lymph nodes, and Nottingham Prognostic Index.

### Bank Marketing Dataset

This dataset was used for the regression and classification tasks.

For regression, the target variable was call duration. For classification, the target variable was whether a customer subscribed to a term deposit.

## Methods Used

### Unsupervised Learning

- Principal Component Analysis (PCA)
- K-Means clustering
- Hierarchical clustering
- Elbow method
- Silhouette score
- Dendrogram analysis

### Regression

- Linear Regression
- Random Forest Regression
- XGBoost Regression
- MAE, MSE, and R-squared
- Residual analysis
- Feature importance analysis

### Classification

- Logistic Regression
- Decision Tree Classifier
- XGBoost Classifier
- Accuracy, precision, recall, F1-score, and ROC-AUC
- Confusion matrix
- ROC curve
- Precision-recall curve

## Tools Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- XGBoost

## Main Findings

- PCA helped reduce the dimensionality of the breast cancer dataset while retaining most of the variation in the selected features.
- K-Means and hierarchical clustering both suggested two broad patient groups in the breast cancer dataset.
- For regression, tree-based models performed better than Linear Regression.
- For classification, XGBoost performed best overall across the main evaluation metrics.
- The classification task showed why accuracy alone is not enough when the target variable is imbalanced.

## Limitations and Future Improvements

This project was completed as academic coursework, so there are still parts that could be improved if the analysis were repeated today.

For the unsupervised learning section, the clustering results should be interpreted carefully because clustering identifies patterns in the data but does not confirm clinical categories by itself.

For the regression section, the analysis could be strengthened by reviewing the feature selection process, adding cross-validation, and testing whether model performance remains stable under different feature sets.

For the classification section, future improvements could include stronger handling of class imbalance, more detailed feature interpretation, and additional model validation.

## Repository Structure

```text
02-machine-learning-analysis-project
├── data
│   └── README.md
├── notebooks
│   └── machine_learning_coursework_notebook.ipynb
├── report
│   └── machine_learning_coursework_report.pdf
└── README.md