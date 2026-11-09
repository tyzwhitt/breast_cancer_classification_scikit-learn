# breast_cancer_classification_scikit-learn
Python/google_colab

# Breast Cancer Classification using Scikit-Learn

## Overview
This repository contains a supervised machine learning workflow built to classify breast cancer tumors as either **malignant** or **benign** using the Wisconsin Breast Cancer dataset from `scikit-learn`.

## Dataset Details
- **Source:** `sklearn.datasets.load_breast_cancer`
- **Samples:** 569 patient instances
- **Features:** 30 continuous numeric attributes derived from digitized fine needle aspirate (FNA) images of breast masses (e.g., radius, texture, perimeter, area, smoothness).
- **Target:** Binary classification — Malignant (0) vs. Benign (1).

## Machine Learning Workflow
1. **Data Preprocessing & Splitting:** Partitioned the dataset using an 80/20 train-test split with stratified sampling to preserve class balance. Features were standardized using `StandardScaler`.
2. **Model Selection:** Implemented a `RandomForestClassifier` with 100 estimators. Random Forest is an ensemble bagging technique that averages predictions from diverse decision trees to minimize overfitting and capture non-linear relationships across feature spaces.
3. **Evaluation Metrics:** Evaluated using Accuracy, Confusion Matrix, Precision, Recall, and F1-score to assess performance on both malignant and benign classes.

## Results & Insights
- **Accuracy:** Achieved over 95% classification accuracy on unseen test data.
- **High Sensitivity/Recall:** The model maintains high recall for the malignant class, which is vital in clinical diagnostics to minimize false negatives.
- **Top Features:** Feature importance analysis indicates that measures of tumor size and morphology (such as worst perimeter, worst area, and worst concave points) are the strongest predictors of malignancy.# Breast Cancer Classification using Scikit-Learn

## Overview
This repository contains a supervised machine learning workflow built to classify breast cancer tumors as either **malignant** or **benign** using the Wisconsin Breast Cancer dataset from `scikit-learn`.

## Dataset Details
- **Source:** `sklearn.datasets.load_breast_cancer`
- **Samples:** 569 patient instances
- **Features:** 30 continuous numeric attributes derived from digitized fine needle aspirate (FNA) images of breast masses (e.g., radius, texture, perimeter, area, smoothness).
- **Target:** Binary classification — Malignant (0) vs. Benign (1).

## Machine Learning Workflow
1. **Data Preprocessing & Splitting:** Partitioned the dataset using an 80/20 train-test split with stratified sampling to preserve class balance. Features were standardized using `StandardScaler`.
2. **Model Selection:** Implemented a `RandomForestClassifier` with 100 estimators. Random Forest is an ensemble bagging technique that averages predictions from diverse decision trees to minimize overfitting and capture non-linear relationships across feature spaces.
3. **Evaluation Metrics:** Evaluated using Accuracy, Confusion Matrix, Precision, Recall, and F1-score to assess performance on both malignant and benign classes.

## Results & Insights
- **Accuracy:** Achieved over 95% classification accuracy on unseen test data.
- **High Sensitivity/Recall:** The model maintains high recall for the malignant class, which is vital in clinical diagnostics to minimize false negatives.
- **Top Features:** Feature importance analysis indicates that measures of tumor size and morphology (such as worst perimeter, worst area, and worst concave points) are the strongest predictors of malignancy.

---

## Author & Attribution

* **Primary Author & Reviewer:** Ty Whittlesey
* **Generative Assistance:** This documentation and workflow summary were generated with the assistance of Gemini (Google, 2026) and subsequently reviewed and edited by Ty Whittlesey for technical accuracy and alignment with coursework requirements.

### Reference

Google. (2026). *Gemini* (November 2026 version) [Large language model]. https://gemini.google.com/
