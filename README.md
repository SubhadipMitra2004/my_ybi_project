# 📌 Simple Linear Regression – Salary Prediction

This project demonstrates a **Simple Linear Regression** model that predicts an employee’s salary based on their years of experience.

---

## 📊 Project Overview
We use a publicly available **Salary Data** dataset with two columns:

- **Experience Years** (independent variable)
- **Salary** (dependent variable)

Our goal is to train a model that can predict salary for any given years of experience.

---

## ⚙️ Workflow

1. **Data Loading & Preprocessing**
   - Loaded the dataset from [GitHub dataset link](https://github.com/ybifoundation/Dataset/raw/main/Salary%20Data.csv).
   - Verified data integrity (no missing values).
   - Selected `Experience Years` as feature (X) and `Salary` as target (y).

2. **Train–Test Split**
   - Split dataset into training (70%) and testing (30%) sets using `train_test_split`.

3. **Model Selection & Training**
   - Used `LinearRegression` from scikit‑learn.
   - Fitted the model on the training data.

4. **Prediction & Evaluation**
   - Predicted salary for test data.
   - Evaluated performance with error metrics and R² score.

---

#Results

| Metric | Value |
|--------|-------|
| **MAE** | 4005.93 |
| **MAPE** | 6.38% |
| **MSE** | 24,141,421.67 |
| **RMSE** | 4913.39 |
| **R² Score** | 0.9602 |

✔️ **R² = 0.96** → The model explains **96%** of the variance in salaries.  
✔️ Predictions are within **₹4,000** on average.

---

# Features

- ✅ Simple and interpretable linear regression.
- ✅ Allows user input to predict salary

