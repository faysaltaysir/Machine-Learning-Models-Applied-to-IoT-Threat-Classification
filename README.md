# Machine Learning Models Applied to IoT Threat Classification

This project presents a comparative analysis of different machine learning algorithms to classify IoT (Internet of Things) threats using a real-world dataset. The goal is to identify the most accurate model to help detect cybersecurity attacks in IoT networks effectively.

## 🔍 Overview

IoT devices are increasingly used in critical environments, but they often lack proper security measures. This makes them vulnerable to various cyber threats. In this project, we implement and compare several machine learning models to classify different types of network threats based on captured traffic data.

## 📁 Dataset

The dataset used in this project is a labeled collection of network traffic features that indicate either normal behavior or specific types of attacks in an IoT environment. It contains multiple columns of numerical and categorical features.

> **Note:** The dataset used is assumed to be already cleaned and labeled.

- Features: 37 (after preprocessing)
- Classes: Multiple threat types including Normal, DoS, Probe, R2L, U2R, etc.
- Size: [Include dataset size if known]

## 🛠️ Technologies & Libraries

- **Programming Language:** Python
- **Libraries:**
  - `pandas` – for data manipulation
  - `numpy` – numerical operations
  - `scikit-learn` – machine learning models and metrics
  - `matplotlib` / `seaborn` – data visualization

## 🚀 Models Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Random Forest


