# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the presence of heart disease using patient medical data.
A Decision Tree model is used to classify whether a patient has heart disease or not.

---

## 📂 Dataset

The dataset contains medical attributes such as:

* Age
* Sex
* Chest Pain Type (cp)
* Cholesterol (chol)
* Maximum Heart Rate (thalach)
* And other clinical features

Target variable:

* `hd` → 0 (No Disease), 1 (Disease)

---

## 🔧 Steps Performed

### 1. Basic EDA

* Checked dataset shape
* Verified data types
* Checked missing values and duplicates

### 2. Data Cleaning

* Replaced invalid values (`?`)
* Converted object columns to numeric
* Handled missing values
* Removed duplicates

### 3. Data Visualization

* Bar plots → categorical distribution
* Histograms → numerical distribution
* Boxplots → feature vs target comparison
* Heatmap → correlation analysis

### 4. Feature Engineering

* Converted data types
* Handled missing values

### 5. Feature Selection

* Separated input features (X) and target (y)

### 6. Model Building

* Applied Decision Tree Classifier

### 7. Model Evaluation

* Accuracy: ~52%
* Used confusion matrix and classification report

---

## 📊 Results

The model achieved approximately **52% accuracy**.
It performed better for the majority class compared to other classes.

---

## 📈 Future Improvements

* Convert problem into binary classification
* Use advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning

---

## 🧠 Conclusion

This project demonstrates how machine learning can be used to predict heart disease.
Data preprocessing and visualization played a key role in understanding the dataset.

---

## 🚀 Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## ✨ Author

Deepika
