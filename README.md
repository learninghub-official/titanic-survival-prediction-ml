# 🚢 Titanic Survival Prediction — Machine Learning Classification Project

## 📌 Project Overview

This project demonstrates a complete end-to-end Machine Learning classification workflow using the Titanic passenger dataset. The objective is to predict whether a passenger survived the disaster based on demographic and travel-related features such as age, gender, ticket class, and fare.

The project is designed to showcase practical ML skills including data preprocessing, feature engineering, model training, evaluation, and model comparison using multiple supervised learning algorithms.

This is a strong foundational ML project commonly discussed in interviews because it clearly demonstrates understanding of the full ML lifecycle.

---

## 🎯 Problem Statement

Given historical passenger records, build a machine learning system that can predict survival outcome (Survived = 1, Not Survived = 0).

This is a **binary supervised classification problem** where:
- Input → Passenger attributes
- Output → Survival prediction

---

## 📊 Dataset

Source: Kaggle — Titanic: Machine Learning from Disaster

The dataset contains passenger-level structured data including:

- Passenger class
- Gender
- Age
- Fare
- Family members aboard
- Port of embarkation

The dataset contains missing values and categorical features, making it realistic for ML preprocessing practice.

---

## ⚙️ ML Workflow Implemented

The notebook follows a structured ML pipeline:

### 1️⃣ Data Loading
Dataset loaded using pandas and validated for structure and column types.

### 2️⃣ Exploratory Data Analysis (EDA)
Performed distribution checks and survival comparisons across features to understand patterns.

### 3️⃣ Data Cleaning
Handled missing values using statistical imputation:
- Age → median
- Embarked → most frequent value

### 4️⃣ Feature Engineering
Categorical variables encoded using One-Hot Encoding:
- Sex
- Embarked
- Passenger Class

Numerical features scaled where required.

### 5️⃣ Train-Test Split
Dataset split into training and testing sets to evaluate generalization performance.

### 6️⃣ Model Training
Multiple algorithms were trained to compare behavior and performance.

---

## 🤖 Algorithms Implemented

- Logistic Regression — linear probability-based classifier
- Random Forest — ensemble of decision trees
- Support Vector Machine — margin-based classifier
- Gradient Boosting — sequential ensemble model

Each model was trained using the same preprocessing pipeline for fair comparison.

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy — overall correctness
- Precision — correctness of positive predictions
- Recall — ability to capture actual positives
- F1 Score — balance between precision & recall

A comparison table was generated to select the best model.

---

## 🏆 Result

Random Forest produced the most balanced performance across all metrics and was selected as the final model.

---

## 💼 Real-World Applications

The same classification workflow can be applied to:

- Fraud detection
- Credit risk prediction
- Customer churn prediction
- Medical diagnosis classification

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📷 Project Screenshots

Include:
- Data preview
- Model training outputs
- Metrics table
- Confusion matrices

---

## 👤 Author

Mayank Nagar — AI / ML / Cloud Practitioner
