# 💰 Salary Prediction API (FastAPI + Docker)

A simple end-to-end **Machine Learning deployment project** that predicts **salary based on years of experience** using **Linear Regression**, exposed as a **FastAPI REST API**, and fully **containerized with Docker**.

This project is perfect for beginners who want to understand how a trained ML model moves from a notebook → API → Docker container 🚀

---

## 🚀 What This Project Does

- Trains a **Linear Regression** model on a small dataset
- Saves the trained model using `joblib`
- Loads the model inside a **FastAPI** application
- Exposes a REST API to get salary predictions
- Runs everything inside a **Docker container**

---

## 🧠 Machine Learning Overview

- **Algorithm Used**: Linear Regression  
- **Input Feature**: `YearsExperience`  
- **Target Variable**: `Salary`

### Model Performance
- **R² Score**: `0.99998` (very high accuracy on sample data)

> This indicates a strong linear relationship between experience and salary in the dataset.

---

## 🛠️ Tech Stack

- **Python 3.10**
- **Pandas & NumPy**
- **Scikit-learn**
- **FastAPI**
- **Uvicorn**
- **Docker**

---

## 📦 Installation & Setup (Local)

### 1️⃣ Clone the Repository
```bash
git clone <your-github-repo-url>
cd <repo-folder>
```

### 2️⃣ Build Docker Image
```bash
docker build -t salary-fastapi .
```

### 3️⃣ Run Docker Container
```bash
docker run -p 8000:8000 salary-fastapi
```

## ✅ Conclusion

This project demonstrates a complete **end-to-end machine learning workflow**, starting from model training to real-world deployment. A simple **Linear Regression model** was trained to predict salary based on years of experience, saved as an artifact, and served through a **FastAPI REST API**.

By containerizing the application using **Docker**, the model becomes portable, reproducible, and production-ready. This approach reflects how machine learning solutions are actually delivered in industry — not just as notebooks, but as scalable services.

