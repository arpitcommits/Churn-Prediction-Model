# Bank Customer Churn Prediction

A supervised machine learning project that predicts customer churn in the banking sector using demographic and behavioral customer information. The project compares multiple classification algorithms and evaluates their performance using cross-validation and hyperparameter optimization.

---

## Overview

Customer churn prediction helps banks identify customers likely to leave and enables proactive retention strategies. This project implements an end-to-end machine learning pipeline covering data preprocessing, feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## Dataset

### Target Variable

- **Exited = 0** → Customer Retained
- **Exited = 1** → Customer Churned

The dataset contains customer demographic, financial, and banking-related attributes used for churn prediction.

---

## Methodology

### Data Preprocessing

- Missing value imputation
- Label encoding
- Feature scaling
- SMOTE for class balancing

### Models Implemented

- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

### Model Optimization

- K-Fold Cross Validation
- Grid Search Hyperparameter Tuning

### Evaluation Metrics

- Accuracy
- ROC-AUC Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

- Achieved a **best classification accuracy of 86%**.
- Improved model generalization using **SMOTE** and **Grid Search**.
- Compared the performance of multiple classification algorithms to identify the best-performing model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)

---

## Repository Structure

```text
Churn-Prediction-Model/
│
├── churn.csv
├── customer_churn_prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/arpitcommits/Churn-Prediction-Model.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook customer_churn_prediction.ipynb
```

---

## Future Improvements

- Implement XGBoost and LightGBM
- Add Explainable AI using SHAP
- Deploy the model using Streamlit
- Explore Deep Learning-based churn prediction

---

## Author

**Arpit Singh**

B.S. Earth Sciences  
Indian Institute of Technology Kanpur

GitHub: https://github.com/arpitcommits
