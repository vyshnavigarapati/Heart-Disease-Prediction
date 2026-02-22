# Heart Disease Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a patient has heart disease using Machine Learning algorithms.  
Multiple models were trained and compared to select the best performing model.

---

## 📊 Dataset Information
- Total Records: 302 (after removing duplicates)
- Features: 13
- Target: `target`
  - 0 → No Heart Disease
  - 1 → Heart Disease

---

## ⚙️ Data Preprocessing
- Removed duplicate records
- Split dataset into training and testing sets (80-20)
- Applied different classification models

---

## 🤖 Models Used
1. Logistic Regression
2. Random Forest
3. XGBoost

---

## 📈 Model Comparison

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 78%      |
| Random Forest        | 80%      |
| XGBoost              | 83%      |

> Best Model: Replace with your highest accuracy model.

---

## 🧪 Confusion Matrix Example
[[25  7] [ 3 26]]

-
##Conclusion
-
Among the tested models, the best performing model achieved the highest accuracy and can be used for heart disease prediction.


##Future Improvements
---
Hyperparameter tuning
Cross-validation
Feature importance visualization
Deployment using Flask or Streamlit
