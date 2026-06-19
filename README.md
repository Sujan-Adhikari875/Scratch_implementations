# Scratch_implementations
# Machine Learning From Scratch

This repository contains implementations of Machine Learning algorithms from scratch using Python and NumPy, along with comparisons to Scikit-Learn implementations.

## Files

### 1. Ordinary_squared.ipynb

Implementation of **Ordinary Least Squares (OLS) Linear Regression**.

#### Topics Covered

* Linear Regression fundamentals
* Ordinary Least Squares (OLS) method
* Parameter estimation using matrix operations
* Prediction using learned coefficients

#### Libraries Used

* NumPy
* Scikit-Learn (for comparison)

#### Workflow

1. Load dataset.
2. Add bias term to the feature matrix.
3. Compute model parameters using the OLS equation.
4. Extract bias and weights.
5. Make predictions.

---

### 2. Scratch_Implementations.ipynb

Implementation of **Linear Regression using Gradient Descent from Scratch**.

#### Topics Covered

* Gradient Descent Optimization
* Linear Regression
* Cost Minimization
* Parameter Updates

#### Libraries Used

* NumPy

#### Workflow

1. Initialize weights and bias.
2. Compute predictions.
3. Calculate errors.
4. Compute gradients.
5. Update parameters iteratively.
6. Generate final predictions.

---

## Requirements

Install the required packages:

```bash
pip install numpy scikit-learn
```

---

## Example Dataset

```python
x = np.array([[1], [2], [3], [4], [5]])
y = np.array([2, 4, 6, 8, 9])
```

---

## Learning Objectives

By studying these notebooks, you will learn:

* How Linear Regression works internally.
* Difference between OLS and Gradient Descent.
* Matrix-based parameter estimation.
* Building machine learning models without relying entirely on libraries.
* Understanding the mathematics behind regression algorithms.

---

## Future Improvements

* Logistic Regression from Scratch
* K-Nearest Neighbors (KNN)
* Decision Trees
* Random Forest
* Support Vector Machines (SVM)
* Neural Networks

---

## Author

Adhikari Sujan

Machine Learning & Data Science 

Focused on understanding algorithms from first principles and implementing them from scratch using Python.
