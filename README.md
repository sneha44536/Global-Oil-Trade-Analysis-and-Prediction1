# 🛢️ Global Oil Trade Analysis and Prediction (EDA + Machine Learning)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-E06E7F.svg?style=for-the-badge&logo=matplotlib&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

# 🌍 Project Overview

This project analyzes **global oil import, export, production, and consumption patterns** using real-world country-wise data.

It also builds **machine learning regression models** to predict:
- Oil transport quantity
- Export values
- Import values

---

# 💡 Problem Statement

Global oil trade depends on:
- Production capacity
- Consumption demand
- Proven reserves
- Import/export imbalance

👉 The goal is to:
- Understand global oil dependency
- Identify top import/export countries
- Predict oil trade flow using ML models

---

# ⚙️ How the Project Works

## 1️⃣ Data Preprocessing
- Load dataset using Pandas
- Clean column names
- Remove missing values
- Encode categorical data (Country)

---

## 2️⃣ Feature Engineering

```python
Oil_Transport = data['Exports'] + data['Imports']
