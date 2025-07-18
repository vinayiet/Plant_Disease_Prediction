# 🌿 Plant Disease Prediction using Environmental Data

## 📌 Problem Statement

Plant diseases are a major contributor to agricultural losses across the globe. Many of these diseases—especially fungal infections—are triggered by specific environmental conditions. Early prediction of disease outbreaks can help farmers take timely preventive actions such as targeted pesticide application or improved irrigation planning.  

This project aims to develop a machine learning model that predicts the likelihood of plant disease occurrence based on environmental parameters like temperature, humidity, rainfall, and soil pH.

---

## 📂 Dataset Overview

This synthetic dataset contains **10,000 samples** collected from various simulated farm locations. Each row in the dataset represents environmental conditions and whether a plant disease was present.

### 🧪 Features:

- `temperature`: Ambient temperature in °C  
- `humidity`: Air humidity in percentage (%)  
- `rainfall`: Amount of rainfall in millimeters (mm)  
- `soil_pH`: Soil acidity or alkalinity  
- `disease_present`: Target label — 0 (Healthy) or 1 (Diseased)

---

## 🎯 Objective

Build a binary classification model that accurately predicts whether a disease is likely to occur under given environmental conditions.

---

## 🛠️ Tools & Technologies

- Python
- Scikit-learn
- Pandas, NumPy, Matplotlib
- Jupyter Notebook
- Streamlit (for optional web-based UI)

---

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies
   ```bash
   pip install -r requirements.txt
