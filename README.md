# Churn Model MLOps Demo

A simple end-to-end MLOps demonstration project for customer churn prediction using Machine Learning, FastAPI, and Python.

---

## 📌 Project Overview

This project demonstrates how a Machine Learning model can be trained, saved, deployed, and served through an API using basic MLOps practices.

The system predicts whether a telecom customer is likely to churn (leave the service) based on customer-related features such as:

- Age
- Customer tenure
- Monthly charges
- Total charges
- Number of support calls

The project covers:

- Synthetic dataset generation
- Model training and evaluation
- Model serialization
- REST API deployment
- Real-time prediction serving

---

## 🚀 Features

- Synthetic telecom churn dataset generation
- Machine Learning model training using Random Forest
- Model performance evaluation
- Saved trained model using Joblib
- REST API using FastAPI
- Swagger API documentation
- Real-time churn prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- FastAPI
- Uvicorn
- Joblib

---

## 📂 Project Structure

```text
churn-model/
│
├── data/
│   └── churn_data.csv
│
├── models/
│   └── churn_model.pkl
│
├── generate_data.py
├── train.py
├── api.py
├── requirements.txt
└── README.md
