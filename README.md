# ml-model-selection-demo
# 📈 Polynomial Regression: Ridge vs. OLS (Work Sample)

This project demonstrates a small but complete machine learning workflow using polynomial regression, Ridge regularization, and cross-validation.

The goal is to evaluate how regularization and dataset size affect generalization performance in noisy regression tasks.

---

## 🧠 Project Overview

- **Problem**: Recover a sinusoidal signal from noisy data using polynomial regression.
- **Challenge**: Avoid overfitting on a small dataset.
- **Approach**: 
  - Compare Ordinary Least Squares (OLS) with Ridge regression
  - Use 5-fold cross-validation to select the best regularization parameter (λ)
  - Evaluate models on a separate test set
  - Retrain the best model on a larger dataset to assess the impact of training size

---

## 📊 Highlights

- 6 Ridge models trained with different λ values
- Cross-validation used to find the best λ based on validation MSE
- Final comparison of three models:
  - Ridge Regression (25 training points, cross-validated λ)
  - OLS (25 training points, λ = 0)
  - Ridge Regression (100 training points)

All models are visualized, and their test MSEs are compared in a final bar chart.

---

## 🛠️ Technologies Used

- Python
- NumPy
- pandas
- matplotlib
- Jupyter Notebook

---

## 📁 Files

- `ML_Work_Sample.ipynb` — Full notebook with code, explanations, and visualizations
- `ML_Work_Sample.pdf` — Exported version for clean viewing

---

## 🙋‍♂️ About Me

Hi! I'm **Daniil Litvinenko**, an incoming TIP intern at Capital One with a strong interest in machine learning. This project was created as a technical work sample to support my application to join the ML team.

Thanks for checking it out!
