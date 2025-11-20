📌 Project Overview

This project focuses on building a credit underwriting model for LoanTap to predict whether a customer is likely to default or not. The project involves exploratory data analysis, feature engineering, handling class imbalance, and developing classification models to support data-driven loan approval decisions.

🧩 Objectives

Understand customer behavior and risk patterns using EDA

Prepare and clean the dataset

Engineer meaningful features for modeling

Handle missing values using KNN imputation

Treat class imbalance with oversampling/undersampling techniques

Build and evaluate Logistic Regression and other ML models

Select the best model based on classification metrics

📁 Project Structure

LoanTap/
│── data/                 # Raw and cleaned datasets
https://drive.google.com/file/d/1Ecm6J3mum2k9zGLJyCgrqetWkWIRfKsF/view?usp=sharing
link for downloading the dataset
│── notebooks/            # Jupyter/Colab notebooks

│── README.md             # Project documentation

🔍 Exploratory Data Analysis

EDA covered:

Distribution of income, loan amount & credit history

Correlation between borrower attributes

Outlier detection & treatment

Identifying patterns of high-risk customers

Visualizations included:

Histograms, boxplots, pair plots

Heatmaps for correlation

Distribution of target variable

🛠 Data Preprocessing

Key steps performed:

Missing value treatment using KNN Imputer

Handling skewed features

One-Hot Encoding for categorical features

Feature scaling using StandardScaler

Train–test split (80–20)

⚖️ Handling Class Imbalance

The dataset contained more cases of one class (non-defaults).
Techniques used:

SMOTE oversampling

Random undersampling

Comparison of results

🤖 Modeling

Models built & evaluated:

Logistic Regression (primary model)

Decision Tree

Random Forest

Gradient Boosting

Logs recorded:

Precision

Recall

F1-score

Accuracy

ROC-AUC

Logistic Regression was preferred due to simplicity, interpretability, and good performance.

📊 Model Evaluation

The final evaluation included:

Confusion matrix

ROC curve

Precision-Recall curve

Feature importance analysis

The model helps identify high-risk borrowers more accurately, enabling better underwriting decisions.

🚀 How to Run

Clone the repository:

git clone(https://github.com/sneha-4515/Data_science_projects/)

Open the notebook:

Collab notebook Loan_Tap.ipynb

Run all cells to reproduce results.

📦 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Imbalanced-learn

Google Colab

🎯 Key Results

Improved classification using balanced data

Better recall for identifying defaults

Created a clean modeling pipeline with reproducible steps

🙌 Author

Sneha
