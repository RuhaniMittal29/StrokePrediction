# Stroke Prediction 📈📊

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Approach and Methodology](#approach-&-methodology)
- [Technology Stack](#tech-stack)

## *Introduction*

Stroke remains one of the leading causes of death and long-term disability worldwide. Its sudden onset and severe consequences make it a major public health concern. ***Early detection and risk assessment*** are vital for enabling timely medical intervention and minimizing damage.

With the rise of digital health records and publicly available datasets, data-driven models have the potential to significantly improve preventative care and clinical outcomes.

This project leverages the ([Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data)) from Kaggle, which includes health-related features such as age, gender, hypertension, heart disease, BMI, smoking status, and glucose levels. 

## *Problem Statement*

The goal is to build a ***machine learning model*** that can accurately ***predict the risk of stroke in individuals based on health-related features***. Such a tool can assist healthcare professionals in identifying high-risk patients for early intervention and monitoring.

## *Approach & Methodology*

- Preprocessed the data by handling missing values, encoding categorical variables, and normalizing features.
- Implemented multiple classification algorithms:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
    - Support Vector Machine (SVM)
- Used pipelines with SMOTE to address class imbalance for each model.
- Evaluated each model individually on performance metrics.
- Built a soft voting ensemble combining all three classifiers.
- Assessed the ensemble model on a separate test set to ensure generalizability and robustness.

## *Tech Stack*
- **Programming Language**: Python
- **Libraries**:
    - `pandas`, `numpy` – Data manipulation
    - `scikit-learn` – Model building, preprocessing
    - `imblearn` – SMOTE for class imbalance
    - `matplotlib`, `seaborn` – Data visualization
    - `Jupyter Notebook` – Development environment

This project demonstrates a practical application of machine learning in healthcare, showcasing a structured workflow, effective handling of imbalanced data, and thoughtful model evaluation techniques.
