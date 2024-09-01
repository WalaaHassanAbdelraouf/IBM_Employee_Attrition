# IBM HR Employee Attrition Analysis

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Objectives](#project-objectives)
- [Analysis Workflow](#analysis-workflow)
  - [1. Data Overview](#1-data-overview)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Data Preprocessing](#3-data-preprocessing)
  - [4. Model Building](#4-model-building)
  - [5. Model Evaluation](#5-model-evaluation)
  - [6. Key Findings](#6-key-findings)
- [Results](#results)
- [Conclusion](#conclusion)


## Overview
This project aims to analyze the IBM HR Employee Attrition dataset to identify patterns and factors contributing to employee turnover. By exploring the relationships between various employee attributes and their likelihood of leaving the company, the project seeks to uncover actionable insights that can inform HR policies and retention strategies.

## Dataset
The dataset used in this analysis is the [IBM HR Analytics Employee Attrition dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) from Kaggle. It contains data on 1,470 employees with 35 features, including personal information, job-related data, compensation details, performance metrics, and behavioral indicators.

## Project Objectives
- **Identify Key Factors:** Determine which factors are most strongly associated with employee attrition.
- **Predictive Modeling:** Build predictive models to classify employees into attrition and non-attrition categories based on their attributes.

## Analysis Workflow

### 1. Data Overview 
We began by loading the dataset and checking for missing values, as well as getting an initial sense of the dataset's structure and key Feature Understanding, Summary statistics and basic visualizations (like histograms) are used to understand the spread and distribution of features, including age, income, and years at the company.

### 2. Exploratory Data Analysis (EDA)
We explore the relationships between various features and the target variable 'Attrition' using visualizations like bar plots, heatmaps, and pair plots.
- Key Insights: Identified features that have strong associations with attrition, such as job satisfaction, work-life balance, overtime, income, and commute distance.

### 3. Data Preprocessing
- Handling Missing Values: Checked for any missing values in the dataset, ensuring data completeness.
- Encoding Categorical Variables: Categorical features were encoded using techniques such as one-hot encoding.
- Scaling: Numerical features were scaled using standard scaling techniques to improve model performance.

### 4. Model Building
- Model Selection: We trained several models, including Logistic Regression, KNN, SVM, Naive Bayes, Decision Tree, Random Forest, Gradient Boost, AdaBoost, and XGBoost classifiers to predict employee attrition.
- Hyperparameter Tuning: Used Grid Search and Cross-Validation to fine-tune the models for optimal performance.

### 5. Model Evaluation
- Performance Metrics: The models were evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure a balanced evaluation of both attrition and non-attrition cases.
- Best Model: SVM emerged as the best-performing model with an accuracy of 96%, striking a good balance between complexity and interpretability.

### 6. Key Findings
- Attrition Factors: Analysis revealed that employees with low job satisfaction, frequent overtime, lower income, and long commute distances were more likely to leave.
- Recommendations: Suggested HR strategies include enhancing job satisfaction, promoting work-life balance, addressing compensation concerns, supporting career growth, and optimizing work locations.

## Results
The SVM model was the best-performing model with an accuracy of 96%. The analysis revealed critical factors contributing to employee attrition, which can inform HR strategies to reduce turnover and improve employee retention.

## Conclusion
The IBM HR Employee Attrition project successfully identified key factors influencing employee turnover and provided recommendations for HR interventions. By implementing these insights, organizations can enhance employee satisfaction, reduce attrition rates, and maintain a more stable and productive workforce.

