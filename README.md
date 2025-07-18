
# 🌿 Plant Disease Prediction using Environmental Data

## 📌 Problem Statement

Plant diseases, especially fungal infections, are a major cause of crop losses globally. These diseases are often triggered by environmental factors like high humidity, temperature, and rainfall. Early prediction of disease outbreaks enables farmers to take preventive actions, optimize pesticide use, and improve crop yield.

This project leverages a **Decision Tree Classifier** to predict the likelihood of plant disease based on real-time environmental data.

---

## 📂 Dataset Overview

The synthetic dataset consists of **10,000 samples** simulating diverse environmental conditions across different farm locations. Each sample includes environmental measurements and a binary label indicating plant health.

### 🔑 Features

- `temperature` — Ambient temperature (°C)
- `humidity` — Air humidity (%)
- `rainfall` — Rainfall (mm)
- `soil_pH` — Soil pH value
- `disease_present` — **Target label** (0 = Healthy, 1 = Diseased)

---

## 🎯 Objective

Train a binary classification model using a **Decision Tree** to predict plant disease presence from environmental factors.

---

## 🛠️ Tools & Technologies

- Python
- Scikit-learn (DecisionTreeClassifier)
- Pandas, NumPy, Matplotlib
- Jupyter Notebook
- **Streamlit** (for web UI)

---

## 🚀 Getting Started

Follow these steps to set up the project, train the model, and launch the Streamlit app:

### 1. Clone the Repository

```bash
git clone https://github.com/vinayiet/plant-disease-predictor.git
cd plant-disease-predictor
```

---

### 2. Create a Virtual Environment

```bash
# Create environment with Python 3.10
conda create --name plant_env python=3.10

# Activate the environment
conda activate plant_env
```

---

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

`requirements.txt` should include:

```
pandas
numpy
scikit-learn
matplotlib
streamlit
```

---

### 4. Train the Model (Optional)

Run the training script to train the model and export `plant_disease_detection_model.pkl`:
Or, open and run the notebook:

```bash
jupyter notebook model.ipynb
```

---

### 5. Run the Streamlit App

```bash
streamlit run app.py
```

This will open the app in your web browser.

---

### 6. Use the App

Enter environmental parameters in the input fields:

* 🌡️ Temperature
* 💧 Humidity
* 🌧️ Rainfall
* 🌱 Soil pH

Click **"Predict Disease Status"** to get a prediction:

* ✅ Healthy
* ⚠️ Diseased

---

### 🧪 Troubleshooting

* If `streamlit` is not recognized, reactivate your environment.
* If `plant_disease_detection_model.pkl` is missing, ensure `train_model.py` ran successfully.
* Confirm all libraries from `requirements.txt` are installed.

---

## 📈 Potential Applications

* Smart farming platforms
* Weather-based plant disease alert systems
* Precision agriculture dashboards

---

## 🤝 Contributions

Contributions are welcome! Fork the project and submit pull requests for improvements.

---
