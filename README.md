# Diabetes Prediction Analysis

This repository contains analyses of CDC diabetes survey data using a variety of machine learning methods — from classical models like logistic regression and decision trees to neural network approaches including perceptrons, feedforward networks, and CNNs. The goal is to predict diabetes diagnosis and compare model performance and predictors across methods.

---

## Project Overview

The dataset includes over 250,000 individuals with demographic, lifestyle, and health features aimed at identifying predictors of diabetes diagnosis (binary outcome).

This project is divided into two main parts:

- **Classical Machine Learning Models:**  
  Logistic regression, SVM, decision tree, random forest, and AdaBoost models were built to predict diabetes status and identify important predictors. Model performance was assessed using AUC scores.

- **Neural Network Models:**  
  Perceptron, feedforward neural network, and convolutional neural network models were developed to explore how neural methods perform on the same prediction task. Model design, training, and evaluation were performed with metrics including accuracy and AUC.

---

## Dataset

The `diabetes.csv` file contains the following variables (one row per individual):

1. Diabetes status (1 = diagnosed, 0 = not diagnosed)  
2. High blood pressure diagnosis  
3. High cholesterol diagnosis  
4. Body Mass Index (BMI)  
5. Smoker status  
6. Stroke history  
7. Myocardial issues (heart attack history)  
8. Physical activity status  
9. Fruit consumption  
10. Vegetable consumption  
11. Heavy drinking status  
12. Healthcare coverage  
13. Unable to afford doctor visits  
14. Self-assessed general health (1–5)  
15. Poor mental health days (last 30)  
16. Poor physical health days (last 30)  
17. Difficulty climbing stairs  
18. Biological sex  
19. Age bracket  
20. Education bracket  
21. Income bracket  
22. Zodiac sign  

---

## Methods and Models

### Classical Models

- **Logistic Regression:** Baseline model to assess individual predictors and overall performance.  
- **Support Vector Machine (SVM):** Nonlinear classification to capture complex boundaries.  
- **Decision Tree:** Simple interpretable tree to identify key splits and predictors.  
- **Random Forest:** Ensemble of trees to improve robustness and accuracy.  
- **AdaBoost:** Boosting approach to focus on hard-to-classify cases.

Each model’s best predictors were identified via feature importance or coefficient analysis. Performance was evaluated using AUC from ROC curves.

---

### Neural Network Models

- **Perceptron:** Basic linear classifier as a neural baseline.  
- **Feedforward Neural Network:** Multi-layer architecture with ReLU activations and sigmoid output layer.  
- **Convolutional Neural Network (CNN):** Adapted 1D CNN to tabular data to capture local feature interactions.

Models were trained using binary cross-entropy loss and Adam optimizer. Evaluation metrics included accuracy, precision, recall, and AUC. Training progress was visualized through loss and ROC curves.

---
