

# 🏃‍♂️ Fitness Activity Recognition using Machine Learning

A machine learning project to recognize basic human fitness activities — **Sitting**, **Lying Down**, **Standing** and **Moving** — using sensor-based features.
Multiple ML algorithms were evaluated, and **Support Vector Machine (SVM)** was finalized as the most effective model based on performance and generalization.

---

## 📌 Problem Statement

Accurate recognition of human activities is essential for fitness tracking, healthcare monitoring, and smart wearable applications.
This project aims to build and compare traditional machine learning models to classify three basic human activities:

* 🪑 Sitting
* 🚶 Standing
* 🛏️ Lying Down
* 🚶 Moving
---

## 🧠 Models Implemented

The following machine learning algorithms were implemented and evaluated:

* Naive Bayes
* K-Nearest Neighbors (KNN)
* Logistic Regression
* Support Vector Machine (SVM) ✅ *(Final Model)*

---

## 📊 Results Summary

| Model               | Accuracy   | Observations                               |
| ------------------- | ---------- | ------------------------------------------ |
| Naive Bayes         | Low–Medium | Fast but assumes feature independence      |
| KNN                 | Medium     | Sensitive to noise and slower at inference |
| Logistic Regression | Medium     | Limited for non-linear class boundaries    |
| **SVM (Final)**     | **High**   | Best generalization and class separation   |

> 📌 **SVM was selected as the final model** due to its superior accuracy and robustness on unseen data.

---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn (for visualization)

---

## 📁 Project Structure

```
fitness-activity-recognition/
│
├── data/HARSmartphone   # Dataset files
├── notebooks/           # Jupyter notebooks (EDA + experiments)                         
├── requirements.txt     # Dependencies
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/fitness-activity-recognition.git
cd fitness-activity-recognition
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Train & evaluate models

```bash
python src/train.py
```

---

## 🔍 Key Learnings

* Classical ML models can perform well for simple activity recognition tasks.
* SVM provides a strong balance between accuracy and computational efficiency.
* Feature relationships in sensor data violate Naive Bayes assumptions.
* Proper preprocessing significantly impacts classification performance.

---

## 🔮 Future Improvements

* Add deep learning models (CNN/LSTM) for sequence-based activity recognition
* Integrate real-time data from smartphone or wearable sensors
* Extend activity classes (running, climbing stairs, cycling)
* Deploy as a mobile or web application

---

## 📚 Literature Review (Brief)

This project is inspired by prior work in **Human Activity Recognition (HAR)** using wearable sensors. Classical ML models such as SVM, KNN, and Logistic Regression have shown strong performance on small-to-medium datasets, while deep learning models are often computationally expensive. This project focuses on evaluating lightweight ML models and selecting the most effective one for simple fitness activities.

---





