# Diabetes Prediction Models

Comparison of logistic regression, support vector machine (SVM), decision tree, random forest, and AdaBoost models for predicting diabetes diagnosis using health survey data from the CDC.

---

## Project Overview

This project uses a large dataset of over 250,000 individuals from the CDC to predict diabetes diagnosis based on demographic, health, and lifestyle factors. Various classification models are built and compared to identify the strongest predictors and the best-performing model.

The goals include:  
- Building and evaluating logistic regression, SVM, decision tree, random forest, and AdaBoost classifiers  
- Determining the best predictors of diabetes diagnosis for each model  
- Comparing model performance using Area Under the ROC Curve (AUC)  
- Interpreting results to understand predictors’ relevance and model suitability

---

## Dataset

The dataset `diabetes.csv` contains the following columns (one row per individual):  

1. Diabetes status (1 = diagnosed, 0 = not diagnosed)  
2. High blood pressure diagnosis  
3. High cholesterol diagnosis  
4. Body Mass Index (BMI)  
5. Smoking status  
6. Stroke history  
7. Myocardial issues (heart attack history)  
8. Physical activity status  
9. Fruit consumption  
10. Vegetable consumption  
11. Heavy drinking status  
12. Healthcare coverage  
13. Unable to afford doctor visits  
14. Self-assessed general health (1–5)  
15. Poor mental health days (last 30 days)  
16. Poor physical health days (last 30 days)  
17. Difficulty climbing stairs  
18. Biological sex (1=male, 2=female)  
19. Age bracket  
20. Education bracket  
21. Income bracket  
22. Zodiac sign  

---

## Methods

- Data preprocessing and cleaning to handle categorical variables and class imbalance  
- Building classification models:  
  - Logistic regression  
  - Support vector machine (SVM)  
  - Single decision tree  
  - Random forest  
  - AdaBoost  
- Evaluating model performance using AUC from ROC analysis  
- Identifying the best predictor for each model by analyzing feature importance and impact on model performance  
- Visualizing ROC curves and feature importance plots  

---
