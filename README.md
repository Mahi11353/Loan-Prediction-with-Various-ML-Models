# 🏦 Loan Prediction Using Various Machine Learning Models

This project aims to automate the loan approval process by predicting whether an applicant is eligible for a loan using supervised machine learning techniques. The models are trained and evaluated on real-world data set.

## 📌 Objective

To develop a robust ML pipeline that assists financial institutions in quickly and accurately predicting loan approval outcomes based on applicant details provided through online forms.

---

## 📂 Dataset

The dataset consists of features such as:

- **Personal Details**: Gender, Marital Status, Education, etc.
- **Financial Details**: Applicant Income, Coapplicant Income, Credit History, etc.
- **Loan Attributes**: Loan Amount, Loan Term, and more.

The target variable is `Loan_Status` (Y/N), which indicates loan approval.

---
## 🔧 Data Preprocessing

- Missing values were handled using mode or mean imputation.
- Categorical values like `'True'/'False'` were converted into binary format `1/0`.
- One-hot encoding was applied to multi-class categorical columns.
- Outliers were removed using IQR method.
- Skewness was handled using square root transformation.

---

## 🚀 Machine Learning Models Used

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**
4. **Decision Tree**
5. **Random Forest**
6. **Gradient Boosting**

Each model was trained and tested using a train-test split and evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Model Comparison

All model accuracies were compared in a final dataframe and sorted to determine the best performing algorithm.

---

## 📈 Visualization

- Distribution of features like income, loan amount.
- Bar plots and histograms for categorical features.
- Accuracy comparisons using seaborn plots.

---

## ✅ Results

The best-performing models were ensemble-based (Random Forest and Gradient Boosting), with accuracy reaching over **80%**, showing strong predictive capability.

---

## 📌 How to Run

1. Clone the repository or open in Jupyter Notebook.
2. Install dependencies using:
   ```bash
   pip install pandas numpy scikit-learn seaborn matplotlib
