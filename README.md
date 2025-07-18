# 🌿 Plant Disease Prediction using Environmental Data

## 📌 Problem Statement

Plant diseases, particularly fungal infections, are a leading cause of agricultural losses worldwide. These diseases are often triggered by specific environmental conditions such as high humidity, temperature, and rainfall. By predicting disease outbreaks early, farmers can take preventive measures to protect crops, optimize pesticide use, and improve yield.

This project uses a **Decision Tree Classifier** to predict whether a plant is likely to be diseased based on real-time environmental parameters.

---

## 📂 Dataset Overview

The synthetic dataset contains **10,000 samples** simulating various environmental conditions across farm locations. Each sample represents environmental measurements and a binary label indicating plant health.

### 🔑 Features:

- `temperature` — Ambient temperature in degrees Celsius  
- `humidity` — Air humidity in percentage  
- `rainfall` — Rainfall amount in millimeters  
- `soil_pH` — Soil acidity or alkalinity  
- `disease_present` — **Target label** (0 = Healthy, 1 = Diseased)

---

## 🎯 Objective

To train a binary classification model using a **Decision Tree** that can predict the presence of plant disease based on environmental factors.

---

## 🛠️ Tools & Technologies

- Python
- Scikit-learn (DecisionTreeClassifier)
- Pandas, NumPy, Matplotlib
- Jupyter Notebook
- **Streamlit** (for web UI)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/vinayiet/plant-disease-predictor.git
cd plant-disease-predictor
