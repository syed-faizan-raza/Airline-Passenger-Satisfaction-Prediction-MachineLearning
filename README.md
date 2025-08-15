# ✈️ AI-Driven Passenger Satisfaction Prediction for Airlines

A complete end-to-end machine learning pipeline for predicting airline passenger satisfaction using demographic, travel, and service-related features. This project replicates and expands on the methodology described in the original report, combining robust data preprocessing, statistical feature selection, and advanced model optimization to achieve high predictive performance.

---

## 📌 Overview

Airlines constantly seek to improve passenger experiences, but identifying dissatisfied customers early can be challenging. This project leverages machine learning to predict **passenger satisfaction levels** based on various travel attributes such as seat comfort, inflight service, food & drink, and more.

Our pipeline includes:

- **Data preprocessing** for mixed numerical and categorical variables
- **Feature selection** using Chi-Square + `SelectKBest`
- **Model evaluation** with Decision Trees, Random Forests, and multiple SVM kernels
- **Hyperparameter tuning** via `GridSearchCV`
- **Comprehensive evaluation** using accuracy, F1-score, precision/recall, confusion matrices, and ROC curves

---

## 📂 Dataset

The dataset contains labeled passenger survey results with features describing demographics, travel context, and rated service aspects.

**Target Variable:** `satisfaction` — categorical (`satisfied` / `neutral or dissatisfied`)

---

## 🛠 Methodology

1. **Preprocessing**
   - Encoded categorical variables
   - Filled missing values
   - Scaled numerical values using `MinMaxScaler`

2. **Feature Selection**
   - Chi² statistical test
   - Kept the `k` most informative features

3. **Model Training & Tuning**
   - Decision Tree, Random Forest, SVM (Linear, RBF, Poly)
   - GridSearchCV for best hyperparameters

4. **Evaluation**
   - Multiple metrics
   - Visualizations of model performance

---

## 📊 Results

The full breakdown of results, including confusion matrices, ROC curves, and hyperparameter tuning outcomes, is provided in the detailed project report.

📑 **[View Full Project Report](https://syed-raza-portfolio.netlify.app/static/media/airline.0b47f9f1e6ba40e21eea.pdf)**

---

Project Contibutors:
1. Syed Faizan (me)
2. Muhammed Noshin
3. Muhammad Hammad