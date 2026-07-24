# Breast Cancer Classification 🧬

## Project Overview
This project builds a Machine Learning model using **Logistic Regression** to classify breast cancer tumors as either Malignant (خبيث) or Benign (حميد). 

## Dataset
The model uses the built-in **Breast Cancer Wisconsin (Diagnostic) Dataset** provided by `scikit-learn`.
- **Total Instances:** 569 patients.
- **Features:** 30 numeric attributes computed from digitized images of a fine needle aspirate (FNA) of a breast mass.

## Technologies & Libraries Used
- **Python** 
- **Scikit-Learn** (for modeling, preprocessing, and metrics)
- **Google Colab** (for development environment)

## Project Workflow
1. **Data Loading:** Extracted the dataset directly from `sklearn.datasets`.
2. **Data Splitting:** Divided the data into 80% Training and 20% Testing to prevent data leakage using `train_test_split`.
3. **Feature Scaling:** Applied `StandardScaler` to normalize feature ranges, ensuring the model doesn't falsely prioritize features with larger numerical values.
4. **Model Training:** Trained a `LogisticRegression` classifier on the scaled training data.
5. **Evaluation:** Evaluated the model using `accuracy_score` and a detailed `classification_report` to monitor Precision, Recall, and F1-score for both diagnostic classes.
