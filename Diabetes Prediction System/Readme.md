# 🩺 Diabetes Prediction System

A Machine Learning project that predicts whether a person is diabetic or not using health-related medical parameters.  
This project includes data analysis, machine learning model building, and deployment using Streamlit.

---

## 📌 Project Overview

The goal of this project is to analyze diabetes-related health data and build a predictive model that can classify whether a person has diabetes based on medical inputs.

The project follows the complete Machine Learning pipeline:
- Data Analysis
- Data Visualization
- Model Training
- Model Evaluation
- Deployment using Streamlit

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Dataset Features

The dataset contains the following medical attributes:

- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Machine Learning Workflow

### 1. Data Loading
Dataset loaded using Pandas.

### 2. Data Analysis
Performed:
- Shape & structure analysis
- Statistical summary
- Missing value checking

### 3. Data Visualization
Used:
- Countplot
- Histograms
- Correlation Heatmap

### 4. Feature & Target Split
Separated input features and target variable.

### 5. Train-Test Split
Dataset split into training and testing sets.

### 6. Model Training
Used Logistic Regression algorithm for classification.

### 7. Model Evaluation
Evaluated model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 8. Model Saving
Saved trained model using Pickle.

### 9. Deployment
Deployed the trained model using Streamlit.

---

## 🚀 Streamlit Application

The web application allows users to:
- Enter medical details
- Predict diabetes status instantly
- View prediction results interactively

---

## ▶️ How to Run the Project

### Step 1: Install Requirements

```bash
pip install -r requirements.txt