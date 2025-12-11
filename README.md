Cardiovascular Disease Prediction — Machine Learning & EDA

This project is an end-to-end Machine Learning workflow for predicting cardiovascular disease using structured health data. It includes data cleaning, exploratory data analysis (EDA), model training, evaluation, and a Gradio-based medical-style report generator.

📓 Project File
Saral_Jain.ipynb

This notebook contains:

Dataset loading & preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Model building (Logistic Regression, Random Forest, XGBoost)

Hyperparameter tuning

Performance evaluation

Medical-style rule-based report generator

Gradio UI for interactive prediction

🧬 Dataset

The notebook uses a cardiovascular dataset with features such as:

Age

Height

Weight

BMI

Systolic/Diastolic Blood Pressure

Cholesterol

Glucose

Smoking

Alcohol intake

Physical activity

Target variable: cardio (0 = No Disease, 1 = Disease)

You should place the dataset in the same environment where the notebook runs.

🔍 Exploratory Data Analysis

The notebook performs:

Distribution plots for numerical features

Count plots for categorical variables

Correlation heatmap

Outlier detection

Relationship visualizations between risk factors and disease presence

🤖 Machine Learning Models

The following models are trained and compared:

Logistic Regression

Random Forest Classifier

XGBoost Classifier (Best Model)

Techniques included:

Scaling & normalization

Train-test split

Stratified K-Fold validation

RandomizedSearchCV for hyperparameter tuning

Feature importance analysis

🩺 Medical-Style Report Generator

The notebook includes a deterministic rule-based engine that:

Takes patient health inputs

Analyzes risk factors

Generates a detailed medical-style text report

Works together with the ML prediction for better interpretability

🌐 Gradio Web App

A Gradio interface is included to:

Input patient health parameters

Generate ML predictions

Display an auto-generated medical explanation

Launch it by running:

gr.launch()

🚀 How to Run
Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn xgboost gradio joblib

Run Notebook

Open Saral_Jain.ipynb in:

Google Colab

Jupyter Notebook

VS Code

Kaggle Notebook

Execute all cells in order.

📈 Results

XGBoost achieved the highest overall performance

Blood pressure, age, cholesterol, and BMI show high influence

Combined ML + rule-based reports improve interpretability for non-technical users

📜 License

This project is free to use for personal, learning, and academic purposes.


<p align="center">

  <!-- Project Status -->
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />

  <!-- Python Version -->
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />

  <!-- License -->
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />

  <!-- Notebook -->
  <img src="https://img.shields.io/badge/Notebook-Jupyter-orange?style=for-the-badge&logo=jupyter" />

  <!-- Machine Learning -->
  <img src="https://img.shields.io/badge/Machine%20Learning-Enabled-purple?style=for-the-badge&logo=googlecolab" />

  <!-- XGBoost -->
  <img src="https://img.shields.io/badge/Model-XGBoost-red?style=for-the-badge&logo=xgboost" />

  <!-- Gradio -->
  <img src="https://img.shields.io/badge/UI-Gradio-0099ff?style=for-the-badge&logo=gradio" />

</p>

