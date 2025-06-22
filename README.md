
# Heart Disease Prediction

## 🎯 Task Objective

The objective of this project is to build a machine learning model that predicts whether a person is at risk of heart disease based on their health metrics. The focus is on:
- Data cleaning
- Exploratory Data Analysis (EDA)
- Model training (Logistic Regression / Decision Tree)
- Evaluation using classification metrics
- Feature importance analysis

---

## 📊 Dataset Used

- **Name**: Heart Disease UCI Dataset
- **Source**: Available on [Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Attributes**:
  - Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Rest ECG, Max Heart Rate, Exercise Induced Angina, etc.
  - **Target**: `1` (disease present), `0` (no disease)

---

## 🧠 Models Applied

- **Logistic Regression**: A linear model for binary classification.
- **Decision Tree Classifier** (optional/alternate): A non-linear, tree-based classifier.

---

## 📈 Key Results and Findings

- **Accuracy**: Achieved ~85–88% on test data using Logistic Regression.
- **Confusion Matrix**: Demonstrated good balance between true positives and true negatives.
- **ROC Curve**: AUC score indicated strong discriminatory power of the model.
- **Important Features**:
  - `cp` (chest pain type), `thalach` (maximum heart rate), and `exang` (exercise-induced angina) had high influence on predictions.

---

## 📦 Libraries Used

- `pandas`, `numpy`: Data handling
- `matplotlib`, `seaborn`: Visualization
- `scikit-learn`: ML modeling and evaluation

---

## ✅ Conclusion

This project highlights how machine learning can assist in early detection of heart disease using simple medical attributes. Logistic Regression offers a strong baseline model, and feature insights can help guide clinical diagnostics.
