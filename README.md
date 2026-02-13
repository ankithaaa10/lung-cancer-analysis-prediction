# lung-cancer-analysis-prediction
lung cancer prediction using kaggle dataset
# Lung Cancer Analysis and Prediction

## Overview
This project analyzes risk factors associated with lung cancer and builds predictive classification models using statistical and machine learning techniques.

The dataset consists of 309 individuals with demographic, behavioral, and medical attributes.

## Objectives
- Identify significant predictors of lung cancer
- Analyze associations between demographic and lifestyle factors
- Compare classification models
- Evaluate model performance using Accuracy, Sensitivity, and Specificity

## Dataset
Source: Kaggle – Lung Cancer Dataset  
Observations: 309  
Target Variable: LUNG_CANCER (YES/NO)

## Methods Used
- Independent Sample t-test
- Chi-Square Test
- Logistic Regression
- Decision Tree
- Linear Discriminant Analysis (LDA)
- Correlation Heatmap

## Model Performance

| Model | Accuracy | Sensitivity | Specificity |
|--------|----------|------------|-------------|
| Logistic Regression | 94.4% | 97.4% | 74.4% |
| LDA | 93.5% | 96.7% | 71.0% |
| Decision Tree | 91.5% | 95.2% | 66.7% |

Best Model: Logistic Regression

## Key Findings
- Smoking, Peer Pressure, Chronic Disease, Fatigue, Allergy, and Coughing were significant predictors.
- Logistic Regression showed the best overall performance.

## Tools Used
- R
- Jamovi
- ggplot2
- caret
- MASS
- rpart

## Author
Ankitha  
BSc Statistics and Computer Science  
2024
