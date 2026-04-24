# ❤️ Heart Disease Prediction Project

## 📌 Overview

This project focuses on predicting whether a patient is at risk of heart disease using machine learning techniques. The model is trained on medical data and evaluated using standard classification metrics.

---

## 🎯 Objective

Build a binary classification model to:

* Predict heart disease risk (0 = No Disease, 1 = Disease)
* Understand key medical factors influencing predictions

---

## 📂 Dataset

* Heart Disease dataset (UCI / Kaggle)
* Contains patient health information such as:

  * Age
  * Sex
  * Chest pain type (cp)
  * Cholesterol (chol)
  * Maximum heart rate (thalach)
  * And other clinical features

---

## ⚙️ Steps Performed

### 1. Data Loading

* Loaded dataset using Pandas

### 2. Data Cleaning

* Handled missing values
* Removed duplicate records

### 3. Exploratory Data Analysis (EDA)

* Checked data distribution
* Visualized relationships using:

  * Count plots
  * Box plots
  * Correlation heatmap

### 4. Model Building

Trained two models:

* Logistic Regression
* Decision Tree Classifier

### 5. Model Evaluation

Used the following metrics:

* Accuracy
* Confusion Matrix
* ROC Curve
* ROC-AUC Score

### 6. Feature Importance

* Identified most important features using Decision Tree

---

## 📊 Results

* Logistic Regression gives stable and reliable performance
* Decision Tree helps understand feature importance
* Important features include:

  * Chest pain type (cp)
  * Maximum heart rate (thalach)
  * Cholesterol (chol)
  * Age

---

## 📈 Visualizations

The project includes:

* Heart disease distribution plot
* Correlation heatmap
* ROC curve
* Feature importance graph

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ▶️ How to Run

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

```
jupyter notebook
```

---

## 🧠 Conclusion

This project demonstrates how machine learning can be applied to healthcare data to predict heart disease risk. It highlights the importance of data preprocessing, model evaluation, and feature analysis.

---

## 🚀 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning
* Deploy model as a web app (Flask or Streamlit)

---

## 👤 Author

Sohaib Maan
