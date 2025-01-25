# Sampling


# Sampling Techniques for Machine Learning Models

This repository contains a Google Colab Notebook that demonstrates the application of various sampling techniques to address class imbalance in datasets. The notebook evaluates the performance of these techniques on multiple machine learning models.

## Objective

To explore the impact of sampling techniques on model performance and identify the best practices for handling imbalanced data.

## Techniques Implemented

1. **Oversampling**: Increases minority class samples.
2. **Undersampling**: Reduces majority class samples.
3. **Systematic Sampling**: Samples data at fixed intervals.
4. **Stratified Sampling**: Maintains class proportions in the sample.
5. **Cluster Sampling**: Randomly selects and uses clusters.
6. **Bootstrap Sampling**: Samples data with replacement.

## Machine Learning Models

The following models were tested with each sampling technique:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Results and Observations

- Oversampling performed well on highly imbalanced datasets.
- Stratified Sampling was useful for maintaining class proportions.
- Random Forest And Decision Tree consistently achieved high accuracy across most techniques.
- Cluster Sampling was effective when clusters were meaningful.
