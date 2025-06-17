# MNIST Classification & Model Benchmarking

This project implements and evaluates multiple machine learning models for handwritten digit classification using the MNIST dataset. It covers a wide range of techniques including Gaussian classifiers, logistic regression (with and without regularization), and Support Vector Machines (SVMs) with various kernels. The project emphasizes hyperparameter tuning, model evaluation, and performance benchmarking across binary and multiclass settings.

---

## 📊 Project Objectives

- Apply linear and kernel-based classifiers to digit recognition.
- Develop modular and testable implementations in Python.
- Compare model performance based on accuracy, misclassification rate, and computational efficiency.
- Visualize decision boundaries, support vectors, and kernel behaviors.
- Explore hyperparameter tuning (e.g., λ for regularization, C for SVM).

---

## 🧠 Models Implemented

- **Gaussian Classifier** (Identity and Common Covariance)
- **Logistic Regression**
- **Regularized Logistic Regression**
- **Multiclass Logistic Regression**
- **Support Vector Machines**  
  - Linear Kernel  
  - Polynomial Kernel  
  - RBF Kernel

---

## 📈 Results Summary

| Model                                | Accuracy (%) |
|-------------------------------------|--------------|
| Gaussian (Identity Covariance)      | 87.11        |
| Logistic Regression (Binary)        | 99.89        |
| Regularized Logistic Regression     | 99.86        |
| Multiclass Logistic Regression      | 99.46        |
| SVM (Linear Kernel)                 | 100.00       |
| SVM (Polynomial, RBF)               | >99.9        |

*Best performing model achieved 99.93–100% accuracy on selected digit classes.*

---

## 📂 Structure

- `Project_Component1.ipynb` – Gaussian & Logistic Regression (Binary)
- `Project_Component2.ipynb` – Multiclass Classification
- `Project_Component3_final.ipynb` – SVM Classifiers and Kernel Comparison

---

## ⚙️ Requirements

- Python 3.8+
- NumPy
- scikit-learn
- matplotlib
- Jupyter Notebook

Install dependencies:
```bash
pip install -r requirements.txt
