🩺 Diabetes Prediction – Data Engineering & ML Pipeline
📌 Project Overview

This project implements an end-to-end data pipeline for predicting diabetes using medical data.
It covers data ingestion, data quality checks, exploratory data analysis (EDA), preprocessing, outlier handling, and machine learning model evaluation.

The goal is to compare multiple models and identify the best-performing approach for diabetes prediction.

🗂️ Dataset

Source: diabetes.csv

Records: Pima Indians Diabetes Dataset

Target column: Outcome

0 → Non-diabetic

1 → Diabetic

Features include:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

🛠️ Technologies Used

Python

Pandas – data ingestion and preprocessing

Matplotlib & Seaborn – data visualization

Scikit-learn – machine learning and evaluation

Jupyter Notebook

🔍 Data Processing Pipeline
1. Data Ingestion

Loaded data from CSV using Pandas

Verified schema, data types, and dataset size

2. Data Quality Checks

Checked for missing values

Validated numeric ranges and distributions

3. Exploratory Data Analysis (EDA)

Histograms to analyze feature distributions

Correlation heatmap to identify feature relationships

Target class distribution visualization

4. Outlier Handling

Applied Interquartile Range (IQR) method

Removed rows containing extreme outliers

Improved data consistency and model stability

5. Feature Engineering

Separated features (X) and target (y)

Prepared dataset for machine learning models

🤖 Machine Learning Models

The following models were trained and evaluated:

Logistic Regression

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Random Forest

Naive Bayes

Gradient Boosting

📊 Model Evaluation

Models were evaluated using:

Accuracy

ROC AUC Score

Cross-Validation

Confusion Matrix metrics (TP, TN, FP, FN)

🔥 Best Model

Random Forest

Achieved the highest Accuracy and ROC AUC score

Demonstrated strong generalization performance

📈 Results Visualization

Accuracy comparison bar chart

ROC AUC comparison bar chart

🚀 Future Improvements

Handle class imbalance using SMOTE or class weighting

Feature scaling for distance-based models

Hyperparameter tuning (GridSearchCV)

Model persistence and deployment

Pipeline automation using Airflow

👨‍💻 Author

Charbel Bazouni
Data Engineer

📄 How to Run the Project
pip install pandas seaborn matplotlib scikit-learn
jupyter notebook


Open the notebook and run cells sequentially.

⭐ Key Takeaway

This project demonstrates a data engineer’s approach to building a reliable, scalable, and reproducible machine learning pipeline from raw data to evaluated models.
