# ❤️ Heart Disease Prediction Using Machine Learning (Flask App)

## 📌 Project Overview

This project is a **Machine Learning web application** that predicts whether a person is at risk of heart disease based on medical attributes.
The model is trained on a heart disease dataset and deployed using a **Flask web framework**.

The full ML pipeline includes:

* Data cleaning
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Web deployment using Flask

---

## 📊 Dataset Information

The dataset contains medical features such as:

* Age
* Sex
* Chest pain type
* Blood pressure
* Cholesterol level
* Fasting blood sugar
* ECG results
* Maximum heart rate
* Exercise induced angina
* ST depression

Target:

* `0` → No heart disease
* `1` → Heart disease present

---

## 🧹 Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling (StandardScaler / MinMaxScaler)
* Train-test split

---

## 🧠 Model Building

Algorithms tested:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

Final model selected based on best performance metrics.

---

## 📈 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Precision & Recall
* F1 Score
* ROC-AUC Curve

---

## 🚀 Flask Web Application

A simple web app built using Flask.

### Features:

* User input form for all features
* Real-time prediction
* Clean HTML/CSS interface
* Model loaded using `pickle`

---

## 📂 Project Structure

```
Heart_disease_prediction_model/
│
├── app.py
├── model.pkl
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── dataset/
│   └── heart.csv
└── README.md
```

---

## ⚙️ Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

### 📌 `requirements.txt` file content:

```
flask
numpy
pandas
scikit-learn
matplotlib
seaborn
pickle-mixin
```

> If you used additional libraries (like joblib or xgboost), add them here accordingly.

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Heart_disease_prediction_model.git
```

### 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python app.py
```

---

## 🌐 Run the Application

Open in browser:

```
http://127.0.0.1:5000/
```

---

## 📌 Tech Stack

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Flask
* HTML/CSS

---

## 🎯 Future Improvements

* Deploy on cloud (Render / PythonAnywhere / AWS)
* Hyperparameter tuning for better accuracy
* Add interactive dashboard (Plotly / Chart.js)
* Add downloadable medical report

---

## 👨‍💻 Author

Built as a Machine Learning project for academic learning and deployment practice.

---
