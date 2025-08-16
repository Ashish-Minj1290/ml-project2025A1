visit on link :-  https://ashish-minj1290-ml-project2025a1-app-bsjm38.streamlit.app/
# ❤️ Heart Stroke Prediction App

A simple web application built with **Streamlit** to predict the risk of heart disease using a **Logistic Regression** model.

---

## 📌 Overview

This app allows users to input their health metrics and get an instant prediction of their risk of heart disease. The model is trained on historical health data and provides a binary classification: **High Risk** or **Low Risk**.

---

## 🛠️ Features

- User-friendly interface for inputting health parameters
- Real-time prediction using a pre-trained machine learning model
- Visual feedback for risk assessment

---

## 📦 Requirements

- Python 3.7+
- Streamlit
- Pandas
- Scikit-learn
- Joblib

Install the required packages using:


pip install streamlit pandas scikit-learn joblib

🚀 How to Run

1. Clone the repository:

git clone https://github.com/yourusername/heart-stroke-prediction.git
cd heart-stroke-prediction

2. Download the model files:
```
Ensure the following files are present in the project directory:

. LogisticRegression.pkl
. scaler.pkl
. columns.pkl
```
3. Run the app:
```
streamlit run app.py
```
4. Open the app:

The app will open in your default web browser at (https://ashish-minj1290-ml-project2025a1-app-bsjm38.streamlit.app/)

-------------------------------------------------------------------------------------------------------------------------------------------------------------

🔮 How It Works

The user inputs their health metrics.
The app preprocesses the input to match the model's expected format.
The input is scaled using the provided scaler.
The model predicts the risk of heart disease.
The result is displayed as either "High Risk" or "Low Risk".

📥 Model Files

. LogisticRegression.pkl: Pre-trained Logistic Regression model.
. scaler.pkl: Standard scaler for feature scaling.
. columns.pkl: List of expected columns for the model input.


📊 Example Usage

1. Set the sliders and dropdowns according to your health metrics.
2. Click the "Predict" button.
3. View the prediction result.
