# 🧠 Stroke Prediction System

A Machine Learning based web application that predicts the risk of stroke using patient health data.
This project uses **Python, Scikit-learn, Pandas, and Streamlit** to build and deploy a healthcare prediction system.

---

# 📌 Project Overview

The Stroke Prediction System analyzes patient medical information and predicts whether a person is at high or low risk of stroke.

The project includes:

* Data preprocessing
* Feature encoding
* Machine Learning model training
* Model evaluation
* Streamlit web app deployment

---

# 🚀 Features

* Predict stroke risk in real time
* Interactive Streamlit web application
* Clean and user-friendly UI
* Data preprocessing and missing value handling
* Machine Learning classification model
* Healthcare-based prediction system

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

---

# 📂 Dataset Features

The model uses the following input features:

* Gender
* Age
* Hypertension
* Heart Disease
* Ever Married
* Work Type
* Residence Type
* Average Glucose Level
* BMI
* Smoking Status

---

# 🤖 Machine Learning Workflow

## 1. Data Preprocessing

* Removed unnecessary columns
* Handled missing BMI values using `SimpleImputer`
* Encoded categorical variables using `LabelEncoder`

## 2. Train-Test Split

* Split dataset into training and testing sets

## 3. Model Training

* Used `RandomForestClassifier`

## 4. Model Evaluation

* Accuracy Score
* Classification Report

## 5. Model Deployment

* Saved trained model using Pickle
* Deployed using Streamlit

---

# 📊 Model Performance

* Machine Learning Algorithm: **Random Forest Classifier**
* Task Type: **Classification**
* Evaluation Metrics:

  * Accuracy Score
  * Precision
  * Recall
  * F1-Score

---

# 💻 Installation & Setup

## Step 1: Clone Repository

```bash
git clone <your-github-repo-link>
```

## Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 3: Run Streamlit App

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```plaintext
Stroke-Prediction/
│
├── app.py
├── StrokePrediction.ipynb
├── StrokePrediction.pkl
├── stroke.csv
├── requirements.txt
└── README.md
```

---

# 🧠 Concepts Applied

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Machine Learning Classification
* Ensemble Learning
* Model Serialization
* Web App Deployment

---

# 📈 Learning Outcome

This project helped in understanding:

* End-to-end Machine Learning workflow
* Real-world healthcare prediction systems
* Data preprocessing techniques
* Streamlit deployment
* Model evaluation methods

---

# 👨‍💻 Developed By

**Devashish Potnis**

---

# 📌 Future Improvements

* Improve model accuracy using hyperparameter tuning
* Add visualization dashboard
* Deploy on cloud platforms
* Add authentication system

---

# ⭐ Conclusion

The Stroke Prediction System demonstrates how Machine Learning can be applied in healthcare to assist in early stroke risk prediction through data-driven analysis and real-time deployment.
