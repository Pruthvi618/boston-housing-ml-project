# 🏡 Boston Housing Price Prediction

## 📌 Overview

This project focuses on predicting house prices using different regression techniques and comparing their performance.

---

## 📊 Dataset

* Boston Housing Dataset
* Total samples: 506
* Target variable: **MEDV (Median House Price)**

---

## ⚙️ Models Used

* Linear Regression (Baseline Model)
* Ridge Regression (L2 Regularization)
* Polynomial Regression (Non-linear modeling)

---

## 🔁 Techniques Applied

* Feature Selection: RM, LSTAT, PTRATIO
* Train-Test Split
* Feature Scaling using StandardScaler
* Pipeline for clean workflow
* Hyperparameter tuning using GridSearchCV

---

## 📈 Model Performance

| Model                 | MSE   | R² Score |
| --------------------- | ----- | -------- |
| Linear Regression     | 27.11 | 0.63     |
| Ridge Regression      | 16.11 | 0.78     |
| Polynomial Regression | 16.29 | 0.78     |

---

## 🧠 Insights

* Linear Regression performed as a baseline but showed lower accuracy.
* Ridge Regression significantly improved performance by reducing overfitting.
* Polynomial Regression captured non-linear relationships and achieved performance similar to Ridge.
* Regularization helped stabilize the model and improve generalization.

---

## 🚀 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📂 Project Structure

* Notebook with full implementation
* Data preprocessing and EDA
* Model training and evaluation

---

## 👨‍💻 Author

Pruthvi
