🧬 Breast Cancer Prediction | Machine Learning
📌 Overview

This project predicts whether a breast tumor is malignant or benign using machine learning classification models. It uses medical features extracted from breast mass images to support early cancer detection.

🎯 Objective

Classify tumors as Malignant (M) or Benign (B)

Compare model performance and select the best one

📊 Dataset

Features from Fine Needle Aspirate (FNA) images

Includes radius, texture, area, concavity, symmetry, etc.

Target: Diagnosis (M / B)

🧠 Models Used

Decision Tree Classifier

Logistic Regression (best performance)

📈 Results

Decision Tree Accuracy: ~93%

Logistic Regression Accuracy: ~97%

Logistic Regression showed higher recall, making it more reliable for medical prediction

🛠️ Tools

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Files
Breast-Cancer-Prediction/
│── Breast Cancer Prediction.ipynb
│── dataset.csv
│── README.md

📉 Customer Churn Prediction | Machine Learning
📌 Overview

This project predicts whether a bank customer will churn (leave the bank) based on demographic and financial information. It helps businesses identify at-risk customers and improve retention strategies.

🎯 Objective

Predict customer churn (Yes / No)

Analyze key factors influencing churn

Compare classification models

📊 Dataset

Source: Kaggle

Size: 10,000 records, 14 features

Key features: Age, Geography, Tenure, Balance, Credit Score, Products, Activity status

Target: Churn (0 = Retained, 1 = Churned)

🧠 Models Used

Decision Tree Classifier

Random Forest Classifier (best performance)

Hyperparameter tuning using GridSearchCV

📈 Results

Random Forest achieved ~87% accuracy

Better precision and recall compared to Decision Tree

Key churn factors: Age, Geography, Tenure, Balance, Number of Products

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Customer-Churn-Prediction/
│── Customer Churn Prediction.ipynb
│── dataset.csv
│── README.md
