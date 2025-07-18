````markdown
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

Follow these steps to clone the repository, train the model, and launch the Streamlit app:

### 1. Clone the Repository

```bash
git clone https://github.com/vinayiet/plant-disease-predictor.git
cd plant-disease-predictor
````

---

### 2. (Optional) Create a Virtual Environment

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

### 4. Train the Model

Run the training script to train the model and export `model.pkl`:

```bash
python train_model.py
```

Or, open and run the notebook:

```bash
jupyter notebook model_training.ipynb
```

---

### 5. Run the Streamlit App

```bash
streamlit run app.py
```

This will launch the app in your web browser.

---

### 6. Use the App

Use inputs fields to input environmental parameters:

* 🌡️ Temperature
* 💧 Humidity
* 🌧️ Rainfall
* 🌱 Soil pH

Click **"Predict Disease Status"** to receive prediction:

* ✅ Healthy
* ⚠️ Diseased

---

### 🧪 Troubleshooting

* If `streamlit` is not recognized, activate your environment again.
* If `model.pkl` is missing, make sure `train_model.py` was executed successfully.
* Ensure all libraries from `requirements.txt` are installed.

---

## 📈 Potential Applications

* Smart farming platforms
* Weather-based plant disease alert systems
* Precision agriculture dashboards

---

## 🤝 Contributions

Feel free to fork the project and submit pull requests for improvements!

---