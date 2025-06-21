# Loan-approval-Prediction-
# 🏦 Loan Approval Prediction using Machine Learning

This project predicts whether a loan will be approved (`Loan_Status`) using various customer attributes. It is a **binary classification problem** (`Yes/No` or `1/0`) solved using multiple machine learning models.

---

## 📊 Dataset Overview

Each row in the dataset represents a loan application with the following features:

| Column Name         | Description                                       |
|---------------------|---------------------------------------------------|
| Gender              | Male/Female                                       |
| Married             | Yes/No                                            |
| Dependents          | Number of dependents (0, 1, 2, 3+)                |
| Education           | Graduate/Not Graduate                             |
| Self_Employed       | Yes/No                                            |
| ApplicantIncome     | Income of the applicant                           |
| CoapplicantIncome   | Income of the co-applicant                        |
| LoanAmount          | Loan amount requested                             |
| Loan_Amount_Term    | Term of loan in months                            |
| Credit_History      | 1: good credit history, 0: poor history           |
| Property_Area       | Urban/Semiurban/Rural                             |
| Loan_Status         | Target variable (Yes = approved, No = rejected)  |

---

## 🧠 Algorithms Used

We implemented and compared the following classification algorithms:

- ✅ Logistic Regression
- 🌲 Random Forest Classifier
- 🚀 XGBoost Classifier
- 🌴 Decision Tree Classifier
- 🤝 K-Nearest Neighbors (KNN)
- 🧭 Support Vector Machine (SVM)

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables (Label Encoding / One-Hot Encoding)
   - Feature scaling using StandardScaler or MinMaxScaler

2. **Model Training**
   - Split data into train/test (e.g., 80/20)
   - Train all listed algorithms
   - Use cross-validation for performance reliability

3. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1 Score)

---

## 📈 Results

After evaluating each model, we compare their performance based on accuracy and classification metrics. XGBoost and Random Forest typically performed best, especially on imbalanced data.




