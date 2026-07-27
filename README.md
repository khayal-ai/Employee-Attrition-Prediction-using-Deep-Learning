# Employee Attrition Prediction using Deep Learning

## Overview

This project builds a deep learning model to predict employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. The model identifies employees who are likely to leave based on demographic, job-related, and workplace features.
The project covers the complete machine learning workflow, including data preprocessing, model development, training optimization, and evaluation.

---

## Objectives

- Predict employee attrition (binary classification).
- Build a neural network using TensorFlow/Keras.
- Address class imbalance to improve minority class detection.
- Evaluate model performance using multiple metrics.

---

## Dataset

- **Dataset:** IBM HR Analytics Employee Attrition & Performance.
- **Task:** Binary Classification.
- **Target:** Attrition (0 = No, 1 = Yes).

---

## Data Preprocessing

- Removed duplicate records.
- Dropped irrelevant features.
- Encoded categorical variables.
- One-hot encoding.
- Standardized numerical features.
- Train-test split.
- Checked class imbalance.

---

## Model

**Architecture**

- Dense (32, ReLU).
- Dense (16, ReLU).
- Output (1, Sigmoid).

**Training**

- Adam optimizer.
- Binary Crossentropy loss.
- Early Stopping.
- Class Weights for imbalanced data.
- Threshold tuning for improved recall.

---

## Evaluation

Performance was evaluated using:

- Accuracy.
- Precision.
- Recall.
- F1-score.
- Confusion Matrix.

Training and validation accuracy/loss curves are also included.

---

## Results

The project compares a baseline model with an improved model.

Improvements included:

- Early Stopping.
- Class Weighting.
- Decision Threshold Tuning.

These techniques improved the model's ability to detect employees likely to leave while balancing overall performance.

---

## Technologies

- Python.
- TensorFlow / Keras.
- Scikit-learn.
- Pandas.
- NumPy.
- Matplotlib.


---

## Future Improvements

- Hyperparameter tuning.
- SMOTE for class imbalance.
- Compare with traditional ML models (Random Forest, XGBoost, Logistic Regression).
- Experiment with deeper neural networks.

---

## Skills Demonstrated

- Data preprocessing.
- Feature engineering.
- Deep learning.
- Binary classification.
- Handling imbalanced datasets.
- Model evaluation.
- TensorFlow/Keras.
- Scikit-learn.
