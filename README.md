# 🏥 Disease Prediction from Medical Data
### CodeAlpha Machine Learning Internship — Task 4

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

---

## 📌 Objective
Predict whether a patient is **diabetic or not** using
medical diagnostic data.

---

## 📊 Dataset
| Property | Details |
|---|---|
| Name | Pima Indians Diabetes Dataset |
| Samples | 768 |
| Features | 8 |
| Target | Outcome (0=Non-Diabetic, 1=Diabetic) |

---

## 🔍 Project Workflow
1. Data Loading & Exploration
2. Handling Biologically Impossible Zero Values
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Model Training & Comparison
6. Evaluation — Accuracy, ROC-AUC, Confusion Matrix
7. Feature Importance Analysis

---

## 🤖 Models Used
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 73.38% | 0.8126 |
| SVM | 72.73% | 0.8139 |
| XGBoost | 75.32% | 0.8044 |
| **Random Forest** ✅ | **75.97%** | **0.8256** |

---

## 📈 Key Results
- ✅ Best Model — Random Forest Classifier
- ✅ Top Features — Glucose, Insulin, BMI
- ✅ 5-Fold Cross Validation applied
- ✅ Zero values replaced with median (medical preprocessing)

---

## 🛠️ Libraries Used
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn

---

## 👩‍💻 Author
**Sakshi Chougule**
B.Tech CSE (AI & ML) — Rajarambapu Institute of Technology
CodeAlpha ML Internship 2026
