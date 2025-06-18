## 🚗 Prediction of Auto Insurance Claims
A machine learning-based approach to predict whether a policyholder will file an auto insurance claim using real-world data and ensemble learning techniques.

## 📌 Project Overview
Insurance companies face the challenge of assessing risk accurately to set appropriate premiums. This project builds and evaluates multiple classification models to predict the likelihood of a customer filing a car insurance claim based on historical data.


## 📊 Dataset
- Source: Car Insurance Dataset on Kaggle
- Size: 10,000 records × 18 features
- Target: Whether a claim was filed by the policyholder last year

## 🔍 Features
- Age, Gender, Driving Experience, Education, Income
Vehicle Ownership, Vehicle Year, Speeding Violations, DUIs
Credit Score, Annual Mileage, and more

## 🧠 Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- AdaBoost
- Gradient Boost
- XGBoost
- Gaussian NB

⚙️ Methodology
- Data Preprocessing: Handling missing values (fillna), encoding, and scaling
- SMOTE: Used to address class imbalance
- Exploratory Data Analysis: Visualizations, correlation analysis
- Model Selection: Based on accuracy, precision, recall, and AUC
- Hyperparameter Tuning: Performed using GridSearchCV

🏆 Results
- XGBoost achieved the best performance:
- Accuracy: 85.45%
- AUC Score: 0.92

📈 Evaluation Metrics
- Confusion Matrix
- Accuracy
- ROC Curve
- Precision & Recall











