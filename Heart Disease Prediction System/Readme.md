# Heart Disease Prediction System

A Machine Learning-based web application that predicts the risk of heart disease using patient health parameters.  
The project is built using **Python, Scikit-learn, and Streamlit** and deployed as an interactive web application.

---

## 🚀 Features

- Predicts risk of heart disease
- Interactive Streamlit web interface
- Real-time prediction
- User-friendly design
- Machine Learning classification model
- Model saved using Pickle

---

## 📊 Dataset Features Used

The model predicts heart disease using the following medical parameters:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia

---

## 🧠 Machine Learning Workflow

### 1. Data Collection
Heart disease dataset loaded using Pandas.

### 2. Data Cleaning
- Removed duplicate records
- Checked dataset structure and statistics

### 3. Data Splitting
Dataset divided into:
- Training Data
- Testing Data

### 4. Model Training
Algorithm Used:
- Random Forest Classifier

### 5. Model Evaluation
Evaluation Metrics:
- Accuracy Score
- Classification Report

### 6. Model Deployment
- Model saved using Pickle
- Streamlit used for web app deployment

---

## 📈 Model Performance

- Achieved good accuracy using Random Forest Classifier
- Classification report used for performance analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## ▶️ How to Run Project

### Step 1: Clone Repository

```bash
git clone <your-github-link>
```

### Step 2: Install Requirements

```bash
pip install -r requirements.txt
```

### Step 3: Run Streamlit App

```bash
streamlit run app.py
```

---

## 📂 Project Structure

```bash
Heart-Disease-Prediction/
│
├── app.py
├── heart.csv
├── HeartDiseasePrediction
├── HeartDiseasePrediction.pkl
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

- Add advanced ML algorithms
- Deploy on cloud platforms
- Add graphical health analytics
- Improve model accuracy using hyperparameter tuning

---

## 👨‍💻 Developed By

Devashish Potnis