# Module 12 Report: Credit Risk Classification Analysis

## Overview of the Analysis

### Purpose of the Analysis
The primary goal of this analysis is to develop and assess machine learning models for credit risk classification. The dataset used comprises financial information about loan applicants, with the objective of predicting whether an applicant represents a credit risk (loan_status = 1) or not (loan_status = 0).

### Data Information
The dataset encompasses various financial features related to loan applicants. The key prediction target is the 'loan_status' variable, indicating whether an applicant is considered a credit risk (1) or not (0). The dataset includes 56271 instances of Class 0 (No Credit Risk) and 1881 instances of Class 1 (Credit Risk).

### Machine Learning Process Stages
1. **Data Loading:** The lending_data.csv dataset is read and explored to understand its structure and content.
2. **Data Preparation:** The dataset is preprocessed to separate features (X) and labels (y) for further analysis.
3. **Data Splitting:** The dataset is split into training and testing sets to facilitate model evaluation.
4. **Model Development:** Logistic regression is chosen as the primary classification method due to its suitability for binary classification tasks.
5. **Model Evaluation:** The logistic regression model is evaluated using standard metrics such as accuracy, precision, and recall.

### Methods Used
- **Logistic Regression:** Logistic regression is employed as the primary machine learning method for credit risk classification.

## Results

### Machine Learning Model 1: Logistic Regression

- **Balanced Accuracy:** The logistic regression model achieved a balanced accuracy score of 0.9494.
- **Precision and Recall Scores:**
  - Precision for Class 0: 0.9977
  - Recall for Class 0: 0.9953
  - Precision for Class 1: 0.8451
  - Recall for Class 1: 0.9090

### Machine Learning Model 2: [If applicable]

- **Balanced Accuracy:** Description of balanced accuracy score.
- **Precision and Recall Scores:**
  - Precision for Class 0: Score
  - Recall for Class 0: Score
  - Precision for Class 1: Score
  - Recall for Class 1: Score

## Summary

### Model Performance Comparison
- **Which Model Performs Best:** The logistic regression model demonstrated high overall performance.
- **Performance Considerations:** Model performance may depend on predicting credit risk (1's) or non-credit risk (0's).

### Recommendation
- **Recommended Model:** Logistic Regression
- **Justification:** The logistic regression model achieved high precision and recall scores for both classes, making it a reliable choice for credit risk classification.

---
