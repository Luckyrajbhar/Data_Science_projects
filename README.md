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


🏠 Delhi House Price Prediction | Machine Learning
📌 Overview

This project predicts house prices in Delhi using machine learning regression models. It analyzes property features such as area, BHK, locality, furnishing, and parking to estimate realistic house prices and understand market trends.

🎯 Objective

Predict house prices in different Delhi localities

Identify key factors influencing property prices

Compare regression model performance

📊 Dataset

Source: Kaggle

Size: 1259 rows × 11 features

Key features: Area, BHK, Bathroom, Locality, Furnishing, Parking, Transaction type

Target: Price (INR)

🧠 Models Used

Decision Tree Regressor

Random Forest Regressor (best performance)

📈 Results

Random Forest achieved ~85% R² score

Area, BHK, and locality were the strongest price drivers

Posh localities (Punjabi Bagh, Lajpat Nagar, Vasant Kunj) showed higher prices 

Delhi House Price Prediction

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Delhi-House-Price-Prediction/
│── Delhi House Price Prediction.ipynb
│── dataset.csv

💎 Diamond Price Prediction | Machine Learning
📌 Overview

This project predicts diamond prices using machine learning regression models based on physical and quality attributes such as carat, cut, color, clarity, and dimensions. The goal is to understand pricing patterns and build an accurate predictive model.

🎯 Objective

Predict diamond prices in USD

Analyze factors influencing price

Compare regression model performance

📊 Dataset

Source: Kaggle – Diamonds Dataset

Records: ~50,000 diamonds

Features: Carat, Cut, Color, Clarity, Depth, Table, X, Y, Z

Target: Price (USD) 

Diamond Price Prediction

🧠 Models Used

Decision Tree Regressor

Random Forest Regressor (best performance)

📈 Results

Random Forest R² Score: ~97%

RMSE: ~620

MAE: ~306

Carat was the strongest predictor of price 

Diamond Price Prediction

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Diamond-Price-Prediction/
│── Diamond Price Prediction.ipynb
│── dataset.csv



📦 E-Commerce Product Delivery Prediction | Machine Learning
📌 Overview

This project predicts whether an e-commerce product will be delivered on time or delayed using machine learning classification models. It also analyzes customer behavior and logistics factors affecting delivery performance.

🎯 Objective

Predict on-time vs late delivery

Identify key factors influencing delivery delays

Compare multiple classification models

📊 Dataset

Records: 10,999 orders

Features: Warehouse block, shipment mode, product weight, cost, discount, customer rating, prior purchases

Target: Reached.on.Time_Y.N

0 → Delivered on time

1 → Not delivered on time 

E-Commerce Product Delivery Pre…

🧠 Models Used

Random Forest Classifier

Decision Tree Classifier (best accuracy ~69%)

Logistic Regression

K-Nearest Neighbors 

E-Commerce Product Delivery Pre…

📈 Key Insights

Product weight and cost significantly affect delivery delays

Higher customer care calls indicate delayed deliveries

Customers with more prior purchases receive timely deliveries more often

Shipment mode and warehouse block have minimal impact 

E-Commerce Product Delivery Pre…

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
E-Commerce-Product-Delivery-Prediction/
│── E-Commerce Product Delivery Prediction.ipynb
│── dataset.csv


🧠 Stroke Prediction | Machine Learning
📌 Overview

This project predicts the likelihood of a heart stroke using machine learning classification models based on patient health and lifestyle data. The goal is to assist in early risk identification and preventive healthcare analysis.

🎯 Objective

Predict whether a person is at risk of stroke

Analyze health factors influencing stroke occurrence

Compare multiple classification models

📊 Dataset

Records: 5,110 patients

Features: Age, Gender, Hypertension, Heart Disease, BMI, Avg Glucose Level, Smoking Status, Work Type, Residence Type

Target: stroke (0 = No Stroke, 1 = Stroke) 

Stroke Prediction

🧠 Models Used

Logistic Regression

Support Vector Machine (SVM)

Decision Tree Classifier

K-Nearest Neighbors (KNN)

📈 Results

Logistic Regression, SVM, and KNN achieved ~93.8% accuracy

Decision Tree accuracy: ~91.8%

Age, hypertension, heart disease, glucose level, and BMI are key risk factors 

Stroke Prediction

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Stroke-Prediction/
│── Stroke Prediction.ipynb
│── healthcare-dataset-stroke-data.csv


💰 Loan Approval Prediction | Machine Learning
📌 Overview

This project predicts whether a loan application will be approved or rejected using machine learning classification models. It analyzes applicant financial details, credit score, income, assets, and loan parameters to support data-driven lending decisions 

Loan Approval Prediction

.

🎯 Objective

Predict loan approval status (Approved / Rejected)

Identify key factors influencing loan approval

Compare classification model performance

📊 Dataset

Records: 4,269 applicants

Key features:

Income, Loan Amount, Loan Tenure

CIBIL Score

Education, Employment Status

Movable & Immovable Assets

Target: loan_status (Approved / Rejected) 

Loan Approval Prediction

🧠 Models Used

Decision Tree Classifier (best performing model)

Random Forest Classifier 

Loan Approval Prediction

📈 Results

Decision Tree Accuracy: ~91%

Random Forest Accuracy: ~89%

Key approval factors:

High CIBIL score (>600)

Higher income & assets

Lower number of dependents

Higher loan amount with shorter tenure 

Loan Approval Prediction

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Loan-Approval-Prediction/
│── Loan Approval Prediction.ipynb
│── loan_approval_dataset.csv


🚢 Titanic Survival Prediction | Machine Learning
📌 Overview

This project predicts passenger survival on the Titanic using machine learning classification models. It analyzes demographic and travel-related features to understand survival patterns during the disaster.

🎯 Objective

Predict whether a passenger survived (1) or not (0)

Perform data preprocessing, EDA, and model comparison

Select the best-performing classification model

📊 Dataset

Source: Kaggle – Titanic Dataset

Records: 891 passengers

Key features:

Pclass, Sex, Age

SibSp, Parch

Fare, Embarked

Target: Survived (0 = No, 1 = Yes)

🧠 Models Used

Logistic Regression

Decision Tree Classifier (best performance)

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

📈 Results

Decision Tree Accuracy: ~94% (training)

Test accuracy: ~89%

Survival strongly influenced by:

Gender (female survival higher)

Passenger class

Fare and age

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Project Structure
Titanic-Survival-Prediction/
│── Titanic Prediction.ipynb
│── titanic_train.csv
│── titanic_test.csv



