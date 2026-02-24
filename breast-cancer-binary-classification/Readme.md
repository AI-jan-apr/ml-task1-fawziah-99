## Breast Cancer — Binary Classification

---

## Objective

In this task, multiple **binary classification** models are built and compared to predict whether a tumor is:

- **0 — Malignant (Cancerous)**
- **1 — Benign (Non-cancerous)**

The following models covered in class are used:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

The focus of this task is **model training, evaluation, and comparison** using standard classification metrics.


---

## Dataset

The **Breast Cancer Wisconsin Dataset** from `scikit-learn` is used.

### Dataset Overview

- 569 samples
- 30 numerical features
- Binary target variable
- No missing values

Each feature represents a measurement extracted from a digitized image of a breast mass (e.g., radius, texture, area, smoothness, concavity, symmetry, etc.).

---

## Methodology

The workflow follows these steps:

1. Split the dataset into training and testing sets.
2. Train each classification model independently.
3. Evaluate models using classification metrics.
4. Visualize prediction performance using confusion matrices.
5. Compare models and interpret results.

---

## Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Classification reports and visualized confusion matrices are used for comparison.

---

## Results & Comparison

Model performance is compared by analysing classification reports and confusion matrices.  
A final discussion identifies the best model in terms of performance and explains which metric is most critical in medical diagnosis tasks.

---

## Project Structure

```
breast-cancer-binary-classification/
├── modeling.ipynb
└── README.md
```