🚗 OLA Driver Attrition Prediction – Machine Learning Case Study
📌 Project Overview

This project focuses on predicting driver attrition for OLA using machine learning techniques. The objective is to identify whether a driver is likely to leave the platform, enabling the company to plan retention programs and improve workforce stability.

The work includes EDA, data cleaning, feature engineering, KNN imputation, class imbalance treatment, and building ensemble learning models (Bagging & Boosting).

🧩 Objectives

Understand patterns associated with driver attrition

Explore and visualize trends within the dataset

Handle missing, inconsistent, and skewed data

Apply KNN imputation for missing values

Treat class imbalance using SMOTE / undersampling

Build and compare classification models

Select the best-performing model based on evaluation metrics

📁 Project Structure
OLA_CASE_STUDY/
│── data/                  # Raw and cleaned datasets
https://drive.google.com/file/d/105CLpdxohh-FpgeAllfx30bujSKI0rNN/view?usp=sharing

│── notebooks/             # Analysis and modeling notebooks


│── README.md              # Project documentation

🔍 Exploratory Data Analysis

Key insights derived from EDA:

Distribution of numerical features

Relationship between driver demographics and attrition

Feature correlations and heatmap

Boxplots, histograms, and categorical breakdown

Behavior of high-risk drivers

Visualization tools used:

Matplotlib

Seaborn

🛠 Data Preprocessing

Steps performed:

Missing value treatment using KNN Imputer

Outlier detection & capping

Encoding categorical features (Label/One-Hot Encoding)

Feature scaling using StandardScaler

Train-test split

⚖️ Handling Class Imbalance

The attrition dataset is typically imbalanced. Methods applied:

SMOTE

Random Oversampling

Random Undersampling

Evaluation was compared across these techniques.

🤖 Models Implemented

Both basic and advanced algorithms were tested:

Baseline Models

Logistic Regression

Decision Tree

Random Forest

Ensemble Models

Bagging Classifier

Gradient Boosting

XGBoost / AdaBoost (if used)

The ensemble models generally provided more stable performance due to their ability to handle noisy and unbalanced data.

📊 Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

Final model selection was based on a balance of high recall (important for attrition prediction) and overall model stability.

🚀 How to Run

Clone the repository:

git clone https://github.com/sneha-4515/Data_science_projects/


Open the notebook:

jupyter notebook OLA_driver.ipynb


Run all cells to reproduce the analysis and results.

📦 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Imbalanced-learn

Google Colab / Jupyter

🎯 Key Results

Improved prediction performance after handling class imbalance

Ensemble models produced higher recall and stable classification

Created a clean, reproducible ML pipeline

Identified key driver attributes contributing to attrition

🙌 Author

Sneha

