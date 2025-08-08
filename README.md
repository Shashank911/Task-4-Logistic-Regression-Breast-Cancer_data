# Task 4: Logistic Regression - Breast Cancer Classification

## Objective
Build a binary classification model using Logistic Regression to detect whether a tumor is malignant or benign based on features in the Breast Cancer Wisconsin dataset.

## Dataset
- **Name:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target Variable:** `diagnosis` (`M` = malignant, `B` = benign)

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## Workflow
1. **Data Loading** – Read the dataset using Pandas
2. **Exploratory Data Analysis** – Data types, missing values, class distribution
3. **Preprocessing** – Dropped unnecessary columns and converted target to numeric
4. **Train-Test Split** – 80% train, 20% test
5. **Model Training** – Logistic Regression model using scikit-learn
6. **Evaluation** – Confusion Matrix, Classification Report
7. **ROC Curve & AUC** – Visualized model performance on classification thresholds

## Results
- Achieved high accuracy in classifying tumors
- Visualized model with ROC curve and AUC score
- Interpretation supported by classification report and confusion matrix

## Files
- `task4_logistic_regression.ipynb` – Main notebook
- `breast_cancer.csv` – Dataset
- `README.md` – Project documentation

## Completed on
August 8, 2025

## 🤝 Acknowledgments
This project was completed as part of my AI/ML internship to strengthen binary classification skills using real-world medical data.
