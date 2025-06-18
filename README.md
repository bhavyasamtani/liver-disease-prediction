#Liver Disease Prediction using Machine Learning

As part of a data-driven healthcare analytics initiative, this project focuses on **early detection of liver disease** using supervised machine learning models. Among various health conditions such as cardiovascular disease and diabetes, **liver disease** was chosen due to its increasing prevalence and complex diagnosis. The objective is to build an intelligent model that assists in **classifying patients** as liver-diseased (1) or non-liver-diseased (0) using clinical and demographic features.

---

##  Project Overview

Liver disease is a serious global health threat that can lead to life-threatening complications if not diagnosed early. This project aims to build a classification model that:
- Predicts the presence of liver disease using structured data
- Helps in early detection and timely medical intervention
- Handles class imbalance using **SMOTE**

---

## Problem Statement

> Can we predict liver disease based on patient biochemical and demographic data using machine learning?

---
## Team Members

> Bhavya Samtani

> Jainam Sanjay Zaveri

> Lokesh Dhamodharan

> Priyank Sachin Palshetkar

> Riya Bhatia
---

## Methodology: CRISP-DM

We followed the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology:

1. **Business Understanding**: Early diagnosis of liver disease through predictive modeling  
2. **Data Understanding**: Analyzed and explored patient records with clinical features  
3. **Data Preparation**: Cleaned data, handled null values, encoded categories, and balanced classes using SMOTE  
4. **Modeling**: Applied and compared multiple ML algorithms  
5. **Evaluation**: Assessed model performance using accuracy, precision, recall, F1-score, and ROC-AUC  
6. **Deployment Ideas**: Potential for integration in clinical decision support systems  

---

## Dataset

- Clinical and demographic data of patients
- Includes attributes such as:
  - Age
  - Gender
  - Total Bilirubin, Direct Bilirubin
  - SGPT, SGOT, Albumin, etc.

---

## Machine Learning Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- Gaussian Naive Bayes  
- Support Vector Classifier (SVC)  

---

## Class Imbalance Handling

- Used **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset before training the models.

---

## Evaluation Metrics

- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## Tech Stack

- Python  
- Jupyter Notebook  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn  
- imbalanced-learn (for SMOTE)  

---

## Repository Structure

```
 liver-disease-prediction/
├──  liverDisease_FinalMLProj.ipynb
├──  README.md
├──  data/
│   └── liver.csv (if public)
├──  images/
│   └── confusion_matrix.png
│   └── roc_curve.png
├──  requirements.txt
```

---

##  Key Takeaways

- SMOTE significantly improved model performance on the minority class  
- Random Forest and XGBoost showed the most balanced results  
- Predictive models can aid in **clinical decision support systems** for early liver disease detection.

