#Decision Tree
## Overview

This repository contains implementations of Decision Tree and Random Forest classifiers using the EnjoySport and Iris datasets. The Decision Tree algorithm is a popular machine learning technique used for both classification and regression tasks. It is easy to interpret and visualize, making it a go-to choice for many applications.

## Table of Contents

1. **Introduction to Decision Trees**
2. **EnjoySport Dataset Implementation**
   - 2.1 Load Dataset
   - 2.2 Calculate Entropy
   - 2.3 Calculate Information Gain
   - 2.4 Create Decision Tree
3. **Decision Tree Classifier with Label Encoding**
   - 3.1 Load Dataset
   - 3.2 Label Encoding
   - 3.3 Create and Visualize Decision Tree
4. **Iris Dataset Implementation**
   - 4.1 Load Dataset
   - 4.2 Split Dataset
   - 4.3 Train Decision Tree
   - 4.4 Test Decision Tree
5. **Random Forest Classifier for Iris Dataset**
   - 5.1 Load Dataset
   - 5.2 Split Dataset
   - 5.3 Train Random Forest Model
   - 5.4 Test Random Forest Model
6. **Conclusion**

## 1. Introduction to Decision Trees

A Decision Tree is a flowchart-like tree structure where each internal node represents a feature (or attribute), each branch represents a decision rule, and each leaf node represents an outcome (or class label). The paths from the root to the leaf represent classification rules.

### Key Concepts

- **Entropy**: A measure of impurity or randomness in a dataset. Lower entropy indicates more homogeneity.
  
- **Information Gain**: The reduction in entropy after a dataset is split on an attribute. It helps in selecting the best attribute for splitting the dataset.

### Advantages

- Easy to interpret and visualize.
- Requires little data preparation (no need for normalization or scaling).
- Can handle both numerical and categorical data.

### Disadvantages

- Prone to overfitting, especially with deep trees.
- Can be unstable with small changes in data.

## 2. EnjoySport Dataset Implementation

### 2.1 Load Dataset
The EnjoySport dataset contains examples of sports activities based on attributes such as weather conditions and time.

### 2.2 Calculate Entropy
A function to calculate the entropy of a dataset is implemented, which helps measure the uncertainty in the data.

### 2.3 Calculate Information Gain
This function calculates the information gain of an attribute, which helps in deciding the best attribute to split the dataset.

### 2.4 Create Decision Tree
The main function builds the Decision Tree using recursive splitting based on the attribute with the highest information gain.

## 3. Decision Tree Classifier with Label Encoding

### 3.1 Load Dataset
Similar to the EnjoySport dataset, we load another dataset for classification tasks.

### 3.2 Label Encoding
Categorical variables are converted to numerical values using label encoding, making them suitable for model training.

### 3.3 Create and Visualize Decision Tree
After training the Decision Tree, it is visualized to provide insight into the decision-making process of the model.

## 4. Iris Dataset Implementation

### 4.1 Load Dataset
The Iris dataset is a well-known dataset used for classification tasks involving different species of iris flowers based on their features.

### 4.2 Split Dataset
The dataset is split into training and testing sets to evaluate model performance.

### 4.3 Train Decision Tree
A Decision Tree classifier is trained on the training set to learn the patterns in the data.

### 4.4 Test Decision Tree
The model is tested on the test set, and performance metrics such as accuracy and confusion matrix are calculated.

## 5. Random Forest Classifier for Iris Dataset

### 5.1 Load Dataset
The Iris dataset is reused for Random Forest classification.

### 5.2 Split Dataset
As before, the dataset is split into training and testing sets.

### 5.3 Train Random Forest Model
A Random Forest classifier is trained, which consists of multiple decision trees to enhance prediction accuracy and reduce overfitting.

### 5.4 Test Random Forest Model
The Random Forest model is evaluated on the test set, providing metrics similar to the Decision Tree evaluation.

## 6. Conclusion

This repository demonstrates the implementation of both Decision Tree and Random Forest classifiers, showcasing their effectiveness on the EnjoySport and Iris datasets. By understanding the underlying principles, one can appreciate the strengths and weaknesses of these models in machine learning tasks.
