# 🌱 Carbon Footprint Optimization in Supply Chain Logistics

## 🧠 Overview

This project focuses on building a **deep learning model** that suggests optimal delivery routes with the **lowest possible carbon emissions**. Traditional logistics systems focus on cost and delivery time; we aim to help businesses make environmentally conscious decisions.

---

## 📦 Problem Statement

While minimizing cost and time is crucial in logistics, carbon footprint is often overlooked. This project aims to:

* Predict carbon emissions for given delivery conditions.
* Suggest routes that balance speed, efficiency, and eco-friendliness.

---

## 🚀 Workflow

### 1. **Data Collection**

* Fleet management systems (fuel, vehicle type, cargo weight)
* Weather APIs (temperature, wind, humidity)
* Map services (route info, origin, destination)
* Traffic conditions (average speed, congestion level)

### 2. **Data Preprocessing**

* Missing value imputation
* Standardization of numerical features
* One-hot encoding of categorical features

### 3. **Model Training**

* Deep Neural Network using TensorFlow/Keras
* Inputs: fuel usage, cargo weight, weather, vehicle type, etc.
* Output: Predicted carbon emissions

### 4. **Model Evaluation**

* **MAE** (Mean Absolute Error)
* **RMSE** (Root Mean Squared Error)
* **Percentage Error** of prediction

### 5. **Route Suggestion Engine**

* Predict emissions for multiple possible routes
* Suggest the route with the **lowest predicted emissions**

---

## 🧪 Sample Evaluation Output

```
MAE: 4.52 kg CO₂
RMSE: 5.19 kg CO₂
Average % Error: 7.83%
```

---

## 🛠️ Setup Instructions

### 🔧 Dependencies

```bash
pip install pandas scikit-learn tensorflow xgboost
```

### ▶️ Run the Model

```bash
python regression_model.py  # or Jupyter Notebook version
```

---

## 📈 Future Enhancements

* Integration with **real-time GPS + traffic APIs**
* Multi-stop route optimization (VRP)
* Add slider for cost-time-carbon tradeoffs
* Visual UI for route visualization and comparison

---

## ✅ Goal

Enable businesses to choose not just the **fastest** or **cheapest** routes, but also the **greenest**, contributing to sustainable logistics.

> Made with ❤️ to reduce emissions one route at a time.
