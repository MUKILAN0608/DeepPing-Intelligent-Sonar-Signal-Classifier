# 🚀 DeepPing: Intelligent Sonar Signal Classifier

### 🌟 AI-powered detection of underwater objects using sonar signals. Rock or Mine? DeepPing knows.

---

## 📌 Overview

DeepPing is a machine learning-based sonar signal classifier built with Python and Scikit-learn. It predicts whether an underwater object is a **Rock** or a **Mine** by analyzing sonar signals. The model is trained on the classic Sonar dataset from UCI Machine Learning Repository.

---

## 📊 Features

- Logistic Regression-based classifier
- Real-time prediction support (plug live sensor values)
- Accuracy display for both training and test sets
- Model persistence using `joblib`
- Simple, efficient, and ready-to-deploy Python script

---

## 📈 Dataset

- **Source**: [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- 60 numeric features per sonar reading
- Labels: `R` (Rock) or `M` (Mine)

---

## 📦 How to Run

1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn joblib



