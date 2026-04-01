# 🧠 Customer Satisfaction Prediction System

## 📌 Problem Statement

In modern e-commerce systems, understanding customer satisfaction is critical for improving business decisions.

This project aims to **predict the customer review score for the next order** using historical transactional and behavioral data.

The dataset includes multiple dimensions such as:

* Order status and delivery performance
* Pricing and payment details
* Customer demographics and location
* Product attributes
* Customer reviews

👉 The goal is to build a system that can **accurately estimate customer satisfaction before feedback is given**.

---

## 🎯 Objectives

* Build a machine learning model to predict customer satisfaction
* Design an **end-to-end production-ready pipeline**
* Implement **continuous training and deployment**
* Track experiments and model performance
* Serve predictions through a real-time interface

---

## 🏗️ Project Architecture

This project follows a **modular MLOps-based architecture** consisting of:

### 🔄 1. Training Pipeline

Responsible for building and evaluating the model.

**Steps involved:**

* **Data Ingestion** → Load dataset into DataFrame
* **Data Cleaning** → Handle missing values and remove irrelevant features
* **Feature Engineering** → Transform and prepare data for modeling
* **Model Training** → Train ML model
* **Model Evaluation** → Evaluate using metrics such as MSE

---

### 🚀 2. Deployment Pipeline

Extends the training pipeline to enable **continuous deployment**.

**Additional steps:**

* **Deployment Trigger** → Checks if model meets performance threshold
* **Model Deployment** → Deploys model as a service
* **Model Serving** → Makes predictions available for real-time usage

---

## ⚙️ Tech Stack

| Category               | Tools Used          |
| ---------------------- | ------------------- |
| Programming            | Python              |
| ML Libraries           | Scikit-learn        |
| Pipeline Orchestration | ZenML               |
| Experiment Tracking    | MLflow              |
| Deployment             | MLflow Model Server |
| Frontend               | Streamlit           |

---

## 🔁 End-to-End Workflow

1. Raw data is ingested
2. Data is cleaned and transformed
3. Model is trained and evaluated
4. Metrics and parameters are tracked
5. Model is deployed if it meets criteria
6. Predictions are served via application

---

## 📊 Model Evaluation

The model is evaluated using:

* Mean Squared Error (MSE)
* Model performance tracking via MLflow
* Continuous monitoring of metrics

👉 Only models meeting a predefined threshold are deployed.

---

## ▶️ How to Run the Project

### 🔹 1. Clone Repository

```bash
git clone https://github.com/sharmakash60/-Customer-Satisfaction.git
cd Customer-Satisfaction
```

### 🔹 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 🔹 3. Run Training Pipeline

```bash
python run_pipeline.py
```

---

### 🔹 4. Run Deployment Pipeline

```bash
python run_deployment.py
```

---

### 🔹 5. Run Streamlit App

```bash
streamlit run streamlit_app.py
```

---

## 🧪 Key Features

* ✅ End-to-end ML pipeline
* ✅ Modular and scalable architecture
* ✅ Automated model deployment
* ✅ Experiment tracking and reproducibility
* ✅ Real-time prediction interface
* ✅ Production-oriented design

---

## 📂 Project Structure

```bash
customer-satisfaction/
│── pipelines/          # Pipeline definitions
│── steps/              # Individual pipeline steps
│── data/               # Dataset (if included)
│── models/             # Saved models
│── run_pipeline.py     # Training pipeline runner
│── run_deployment.py   # Deployment pipeline runner
│── streamlit_app.py    # Frontend app
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

---

## 💡 Use Cases

* E-commerce platforms
* Customer experience analytics
* Recommendation systems
* Business decision optimization

---

## 🧠 Key Learnings

* Building production-ready ML pipelines
* Integrating MLflow for experiment tracking
* Deploying models using pipeline orchestration tools
* Designing scalable ML systems
* Connecting backend ML systems with frontend applications

---

## 🚀 Future Improvements

* Add advanced models (XGBoost, Deep Learning)
* Deploy on cloud (AWS / GCP)
* Add real-time data streaming
* Implement monitoring & alerting system
* Improve feature engineering

---

## 📌 Conclusion

This project demonstrates how to build a **complete machine learning system**, from data processing to deployment, with a strong focus on **MLOps practices**.

It showcases how businesses can leverage machine learning to **predict customer satisfaction proactively**, enabling better strategic decisions and improved customer experience.
