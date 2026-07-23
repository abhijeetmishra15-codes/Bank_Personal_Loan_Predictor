# 🏦 Bank Personal Loan Predictor

A Machine Learning project that predicts whether an existing bank customer is likely to accept a **Personal Loan** based on demographic, financial, and banking-related features.

The goal of this project is to help banks identify potential customers for targeted personal loan campaigns, reducing marketing costs and improving conversion rates.

---

## 📌 Project Overview

Banks often offer personal loans to existing customers. Instead of contacting every customer, banks can use machine learning to predict which customers are more likely to accept a loan.

In this project, multiple machine learning algorithms were trained and compared to build an accurate loan prediction model.

---

## 🎯 Problem Statement

Predict whether a customer will accept a personal loan based on customer information such as:

- Age
- Experience
- Income
- Family Size
- Education
- Mortgage
- Credit Card Usage
- Online Banking
- Securities Account
- CD Account
- And other banking features

Target Variable:

**Personal Loan**
- 0 → Loan Not Accepted
- 1 → Loan Accepted

---

## 📂 Dataset

**Dataset:** Bank Personal Loan Modelling Dataset

The dataset contains customer demographic and financial information collected by a bank.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed exploratory analysis including:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Correlation analysis
- Target variable distribution
- Age distribution
- Feature visualization using histograms
- Heatmap for feature correlation

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
  - ID
  - ZIP Code

- Checked for:
  - Missing values
  - Duplicate records

- One-Hot Encoding of categorical variables

- Feature Scaling using StandardScaler

- Train-Test Split

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Support Vector Machine (SVM)

---

## 🔍 Hyperparameter Tuning

Hyperparameter tuning was performed using **GridSearchCV** on the SVM model.

Parameters tuned:

- C
- Gamma
- Kernel (RBF)

This improved the overall prediction performance of the model.

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

The performance of different algorithms was compared to identify the best-performing model.

---

## 📁 Project Structure

```
Bank_Personal_Loan_Predictor/
│
├── Bank_Personal_Loan_Modelling.csv
├── model.ipynb
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Bank_Personal_Loan_Predictor.git
```

Move into the project directory

```bash
cd Bank_Personal_Loan_Predictor
```

Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## ▶️ Run the Project

Open Jupyter Notebook

```bash
jupyter notebook
```

Open

```
model.ipynb
```

Run all cells sequentially.

---

## 📚 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Feature Scaling
9. Model Training
10. Model Evaluation
11. Hyperparameter Tuning
12. Final Prediction

---

## 💡 Real-World Applications

- Personal Loan Marketing
- Customer Segmentation
- Banking Analytics
- Credit Decision Support
- Financial Risk Analysis
- Targeted Customer Campaigns

---

## 🔮 Future Improvements

- Deploy using Flask/FastAPI
- Build an interactive Streamlit web application
- Save trained model using Pickle
- Add SHAP for model explainability
- Perform advanced feature engineering
- Handle class imbalance using SMOTE
- Compare with XGBoost and Random Forest

---

## 📖 Key Concepts Learned

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Classification Algorithms
- Hyperparameter Tuning
- Model Evaluation
- Confusion Matrix
- Precision, Recall & F1 Score

---

## 👨‍💻 Author

**Abhijeet Mishra**

GitHub: https://github.com/abhijeetmishra15-codes

---
