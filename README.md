# 🚢 Titanic Survival Predictor — ML + Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat-square&logo=pandas)
![Jupyter](https://img.shields.io/badge/Notebook-Google%20Colab-yellow?style=flat-square&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> A complete end-to-end Data Science project combining Exploratory Data Analysis and Machine Learning to predict Titanic passenger survival.

---

## 📌 Project Overview

This project analyzes the famous **Titanic dataset** to predict whether a passenger survived or not. It covers the full Data Science pipeline — from raw data to trained models — and is a great showcase of both **analytical thinking** and **ML skills**.

---

## 🎯 What This Project Does

| Stage | Description |
|-------|-------------|
| 📊 **EDA** | Visual exploration of survival by gender, class, age |
| 🧹 **Data Cleaning** | Handle missing values, drop irrelevant columns |
| ⚙️ **Feature Engineering** | Create `FamilySize`, `Title`, `AgeGroup`, `FareBand`, `IsAlone` |
| 🤖 **ML Models** | Train & compare 4 models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting |
| 📈 **Evaluation** | Accuracy, Cross-Validation, Confusion Matrix, Classification Report |
| 🔮 **Custom Prediction** | Predict survival for any custom passenger input |

---

## 📊 Key Insights Found

- 👩 **Women** had a ~74% survival rate vs ~19% for men
- 🎩 **1st class passengers** had the highest survival rate (~63%)
- 👶 **Children** were prioritized in rescue
- 💰 **Fare paid** and **passenger title** are top predictive features
- 🌲 **Random Forest** and **Gradient Boosting** gave the best accuracy (~82–84%)

---

## 🛠️ Technologies Used

- **Python 3.10**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Machine Learning models & evaluation
- **Google Colab** — Development environment

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Upload `titanic_ml_project.ipynb`
4. Click **Runtime → Run all**

### Option 2: Local (Jupyter Notebook)
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook titanic_ml_project.ipynb
```

---

## 📁 Project Structure

```
titanic-survival-predictor/
│
├── titanic_ml_project.ipynb   # Main notebook (all code)
├── README.md                  # Project documentation
│
└── outputs/                   # Generated charts
    ├── survival_overview.png
    ├── class_age_analysis.png
    ├── heatmap_survival.png
    ├── model_comparison.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## 📷 Sample Visualizations

The notebook generates 6 charts:
- 🥧 Survival rate pie chart
- 📊 Survival by gender & passenger class
- 🔥 Heatmap of survival across gender × class
- 📊 Model accuracy comparison
- 🔲 Confusion matrix
- 📉 Feature importance plot

---

## 🙋 About Me

I'm a **2nd year Data Science & AI student** passionate about turning data into meaningful insights. This project is part of my portfolio as I grow my skills in ML and analytics.

---

## 📄 Dataset

- **Source:** [Titanic Dataset — datasciencedojo](https://github.com/datasciencedojo/datasets)
- **Rows:** 891 passengers
- **Target:** `Survived` (0 = No, 1 = Yes)

---

⭐ *If you found this project helpful, please consider giving it a star!*
