# 🍷 MLflow Wine Quality MLOps Project

An end-to-end machine learning experiment tracking project using MLflow.
This project trains multiple models on the Wine Quality dataset and logs metrics, parameters, and models for comparison and reproducibility.

---

## 🚀 Project Overview

This project demonstrates:

* Training multiple ML models
* Experiment tracking with MLflow
* Model performance comparison
* Model registry usage
* Reproducible ML pipeline

The goal is to showcase practical MLOps workflow used in real-world machine learning systems.

---

## 📊 Models Used

* Linear Regression
* Logistic Regression
* Support Vector Machine (SVR)
* Random Forest Regressor
* Decision Tree Regressor

---

## 🗂️ Project Structure

```
.
├── main.py
├── requirements.txt
├── README.md
└── mlruns/
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/mlflow-wine-quality-mlops.git
cd mlflow-wine-quality-mlops
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

Start MLflow UI:

```bash
mlflow ui
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 📈 Metrics Tracked

* RMSE
* MAE
* R² Score
* Accuracy (for Logistic Regression)

---

## 🎯 Key Learning Outcomes

* MLflow experiment tracking
* Multi-model training pipeline
* Model versioning
* Basic MLOps workflow

---

## 🔮 Future Improvements

* Hyperparameter tuning
* CI/CD integration
* Docker containerization
* Cloud deployment
* Automated model selection

---

## 👨‍💻 Author

Your Name

---

⭐ If you found this helpful, consider giving the repo a star!
