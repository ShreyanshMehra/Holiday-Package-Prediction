# Holiday Package Prediction using Machine Learning

This project focuses on predicting whether an employee will purchase a holiday package based on demographic, behavioral, and company-related features. The classification model has been trained using ensemble techniques, including **XGBoost**, **Gradient Boosting**, **Random Forest**, **Decision Tree**, and **AdaBoost**, with hyperparameter tuning for optimal performance.

---

## 📌 Problem Statement

Companies often offer holiday packages to employees as part of benefits programs. However, not all employees opt for them. The objective of this project is to **build a predictive model** that helps the company identify potential buyers of holiday packages in advance, enabling them to personalize marketing efforts and optimize package allocation.

---

## 🧠 Features Used

Some of the key features include:

- Age  
- Gender  
- Type of Employment  
- Duration of Employment  
- Designation  
- Travel History  
- Product Pitch Score  
- Number of Follow-ups  
- Preferred Property Star  
- Number of Children Visiting  
- Monthly Income  

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical features
- Feature engineering for important patterns
- Scaling and normalization

### 2. Exploratory Data Analysis (EDA)
- Distribution plots
- Correlation matrix
- Class imbalance checks

### 3. Model Training & Evaluation

Models used:
- XGBoost (Best performer ✅)
- Random Forest
- Gradient Boosting
- Decision Tree
- AdaBoost

Techniques:
- Hyperparameter tuning (GridSearchCV)
- AUC-ROC Curve evaluation
- Confusion matrix, accuracy, recall, and precision

---

## 🏆 Results

| Model             | Accuracy | AUC Score |
|------------------|----------|-----------|
| XGBoost          | ~84%     | ~0.91     |
| Gradient Boosting| ~83%     | ~0.90     |
| Random Forest    | ~81%     | ~0.88     |
| AdaBoost         | ~79%     | ~0.85     |
| Decision Tree    | ~76%     | ~0.82     |

> 📈 **XGBoost** provided the best overall performance with excellent balance between precision and recall.

---
## 🛠️ Tech Stack

- Python 
- Pandas, NumPy  
- Scikit-learn  
- XGBoost, LightGBM  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Future Improvements

- Incorporate deep learning models  
- Add explainability using SHAP or LIME  
- Implement a web dashboard for real-time prediction using Streamlit or Flask  

---
