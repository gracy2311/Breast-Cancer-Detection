# Breast-Cancer-Detection
🧠 Breast Cancer Detection Using Machine Learning
📋 Overview
This project focuses on building a machine learning model to detect breast cancer (malignant or benign) based on patient diagnostic data. Early and accurate detection is crucial in increasing the survival rates of breast cancer patients, and machine learning helps automate and improve diagnostic accuracy.

🎯 Objective
To develop and evaluate machine learning models that can classify tumors as malignant or benign using labeled medical data (such as features from biopsies).

🧪 Dataset
Name: Breast Cancer Wisconsin (Diagnostic) Dataset

Source: UCI Machine Learning Repository

Size: 569 instances, 30 features

Features include:

Radius, Texture, Perimeter, Area, Smoothness, etc.

Diagnosis (M = Malignant, B = Benign)

🛠️ Technologies Used
Programming Language: Python

Libraries/Frameworks:

pandas, numpy – data preprocessing

matplotlib, seaborn – visualization

scikit-learn – model building (e.g., SVM, Random Forest, Logistic Regression)

joblib – model saving

📊 Workflow
Data Preprocessing

Handling missing values

Feature scaling

Encoding labels

Exploratory Data Analysis (EDA)

Correlation matrix

Distribution of features

Model Training

Logistic Regression

Support Vector Machine (SVM)

Random Forest

K-Nearest Neighbors

Model Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC-AUC Curve

Model Deployment (Optional)

Export trained model using joblib or pickle

Web app using Streamlit or Flask
