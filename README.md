# Customer Churn Prediction & Retention System

## 🚀 Live Demo

**Streamlit App:**
https://customer-churn-prediction-ad6zun7meweswre8bqkwxp.streamlit.app/

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a company.

The project uses customer information such as tenure, monthly charges, contract type, internet service, and other customer details to predict churn.

The model is trained using multiple classification algorithms and **XGBoost** is used for the final prediction system.

## 🎯 Objectives

* Predict whether a customer will churn or stay.
* Analyze important factors affecting customer churn.
* Compare different Machine Learning models.
* Build an interactive web application using Streamlit.
* Help businesses identify customers who may be at risk of leaving.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib
* Streamlit
* Google Colab
* GitHub

## 🤖 Machine Learning Models

The following models were trained and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

The final application uses the trained XGBoost model for prediction.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
XGBoost Model
   ↓
Save Model (.pkl)
   ↓
Streamlit Web Application
   ↓
Deployment
```

## 📊 Dataset

The project uses the **Telco Customer Churn Dataset**.

The dataset contains customer information including:

* Customer demographics
* Account information
* Services used
* Contract details
* Monthly charges
* Total charges
* Churn status

## 📁 Project Structure

```text
customer-churn-prediction/
│
├── app.py
├── requirements.txt
├── customer_churn_model.pkl
└── model_features.pkl
```

### File Description

| File                       | Description                    |
| -------------------------- | ------------------------------ |
| `app.py`                   | Streamlit application          |
| `requirements.txt`         | Required Python libraries      |
| `customer_churn_model.pkl` | Trained Machine Learning model |
| `model_features.pkl`       | Features used by the model     |

## 🌐 Deployment

The application is deployed using **Streamlit Community Cloud** and connected to GitHub.

**Live Application:**
https://customer-churn-prediction-ad6zun7meweswre8bqkwxp.streamlit.app/

## 💡 Key Learning Outcomes

Through this project, I worked on:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature encoding
* Classification algorithms
* Model evaluation
* Feature importance
* Model serialization using Joblib
* Streamlit application development
* GitHub project management
* Machine Learning model deployment

## 👨‍💻 Author

**Syed Mohammed Uvais**

B.Tech Computer Science Engineering (AI & ML)

---

⭐ If you find this project useful, feel free to explore the repository and live application.
