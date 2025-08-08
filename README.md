# 🌡️ AIoT - Environment Status Classifier

This project is an **AI-powered classification system** that analyzes **temperature and humidity** sensor data to detect the **environmental status** as:

- ✅ **Normal**
- ⚠️ **Warning**
- 🔴 **Critical**

It simulates sensor readings, labels them based on conditions, and uses a **Random Forest Classifier** to predict the environmental status.

---

## 📌 Project Goals

- Simulate an AIoT use-case where environmental data (temperature, humidity) is collected.
- Use machine learning to classify the condition as `Normal`, `Warning`, or `Critical`.
- Visualize performance using **confusion matrix** and classification metrics.
- Serve as a learning resource for beginners in **AI + IoT integration**.

---

## 🧪 Dataset

The dataset is synthetically generated using `numpy` to simulate real-world sensor values:
- **Temperature**: 15°C to 40°C
- **Humidity**: 20% to 80%

Based on rule-based logic:
- 🔴 `Critical`: Temp > 35°C and Humidity < 25%
- ⚠️ `Warning`: Temp between 30–35°C and Humidity between 25–35%
- ✅ `Normal`: All other values

---

## 🧠 Machine Learning Model

- Algorithm: `RandomForestClassifier` (Scikit-learn)
- Input features: `temperature`, `humidity`
- Output labels: `status` (Normal, Warning, Critical)
- Evaluation:
  - Classification Report
  - Confusion Matrix (with heatmap)

---

## 📊 Results (Example)

- **Precision**, **Recall**, and **F1-Score** for each class
- Visualized **confusion matrix** with color-coded plot
- High accuracy in correctly detecting environmental status

---

## 🧰 Tech Stack

- Python 3.x
- Numpy
- Pandas
- Scikit-learn
- Matplotlib

---



