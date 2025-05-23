# Stroke Prediction 📈📊

Stroke remains one of the leading causes of death and long-term disability globally. Its sudden onset and severe consequences make it a critical public health concern. Early detection and risk assessment are essential for timely medical intervention, which can significantly reduce the likelihood of severe outcomes. Given the increasing availability of healthcare data, data-driven approaches to stroke prediction have the potential to revolutionize preventative care.

This project leverages the ([Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data)) from Kaggle, which includes health-related features such as age, gender, hypertension, heart disease, BMI, smoking status, and glucose levels. By employing machine learning techniques, the ***goal is to develop a predictive model that accurately classifies individuals at high risk of stroke***. Such a model can be a valuable tool for healthcare professionals, enabling timely interventions and potentially saving lives.

## *Approach & Methodology*

To build a reliable predictive model, multiple classification algorithms were implemented, including **Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM)**. Each model was evaluated individually using pipelines with **SMOTE** to handle class imbalance. Finally, a **soft voting ensemble** was built combining all three models to improve overall performance and robustness. The ensemble model was evaluated on a separate test set to ensure generalizability.
