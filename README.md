# Ridge Regression

A Machine Learning project that demonstrates how **Ridge Regression** helps reduce **overfitting** in Linear Regression models using **L2 Regularization**.

This project explores how adding a penalty term to the cost function improves model generalization and stabilizes coefficient values.

---

## Overview

Traditional Linear Regression models may overfit when:

* Features are highly correlated
* Dataset contains noise
* Model complexity increases

Ridge Regression solves this problem by introducing a **regularization penalty** that shrinks coefficient values.

This project:

* Implements Ridge Regression using Scikit-learn
* Compares Ridge Regression with Linear Regression
* Demonstrates regularization effects
* Explores coefficient shrinkage
* Visualizes model behavior with different alpha values

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Concepts Covered

### 1. Ridge Regression

Ridge Regression is a regularized version of Linear Regression that adds an L2 penalty term.

Cost Function:

```text
J(θ) = Σ(yi - ŷi)² + λΣ(θj²)
```

Where:

* `Σ(yi - ŷi)²` → Residual Sum of Squares
* `λ` → Regularization parameter
* `θj²` → Squared model coefficients

---

### 2. Regularization

Regularization helps:

* Reduce overfitting
* Improve generalization
* Prevent excessively large coefficients

---

### 3. Bias-Variance Tradeoff

The project demonstrates how Ridge Regression balances:

* Model complexity
* Prediction accuracy
* Generalization performance

---

### 4. Coefficient Shrinkage

Ridge Regression reduces coefficient magnitudes instead of eliminating them completely.

---

## Key Insights

The project demonstrates:

* Why overfitting occurs
* How regularization improves model performance
* Effect of increasing alpha values
* Difference between Linear and Ridge Regression
* Importance of controlling model complexity

---

## Learning Outcomes

By completing this project, you will understand:

* What overfitting is
* How Ridge Regression works internally
* L2 Regularization intuition
* Bias-Variance Tradeoff
* Effect of alpha values on model behavior

---

## Repository

GitHub Repository:

```text
https://github.com/priyankasiddaraj76/ridge-regression
```

---

## License

This project is open-source and available under the MIT License.
