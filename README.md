# 💼 AI Job Salary Prediction Using KNN Regression

A Machine Learning project that predicts **AI job salaries in USD** using **K-Nearest Neighbors (KNN) Regression**.

The project includes data preprocessing, feature scaling, K selection, model training, model evaluation, and an interactive **Streamlit dashboard**.

##  Live Demo

👉 https://ai-job-salary-prediction-e7rbkacptdr8mvxnydfaf3.streamlit.app/

##  Project Overview

The goal of this project is to predict the salary of an AI-related job based on important job characteristics.

The model uses:

- Years of Experience
- Remote Ratio
- Job Description Length
- Benefits Score

to predict:

- **Salary (USD)**

## 🧠 Machine Learning Algorithm

### K-Nearest Neighbors (KNN) Regression

KNN Regression predicts a continuous value by looking at the salaries of the nearest similar data points.

The project also uses **StandardScaler** because KNN is distance-based and feature scales can strongly affect the result.

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
StandardScaler
     ↓
Find Best K
     ↓
KNN Regression
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Streamlit Dashboard
