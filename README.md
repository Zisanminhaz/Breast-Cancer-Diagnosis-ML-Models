
# Breast Cancer Diagnosis - Machine Learning Models

This repository contains the implementation of various machine learning models for breast cancer diagnosis using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The models implemented in this repository are based on the research paper titled **"Performance Comparison of Machine Learning and Ensemble Models for Breast Cancer Diagnosis"**, which was published at the **APCIT 2025 Conference**. The paper compares different machine learning models on the task of classifying benign and malignant breast cancer tumors.

**Author**: Minhaz Alam Jisan (1st Author)  
**Conference**: APCIT 2025 Conference

## Models Used:
- **LightGBM** (Light Gradient Boosting Machine)
- **CatBoost**
- **Multi-Layer Perceptron (MLP)**
- **Quadratic Discriminant Analysis (QDA)**
- **Ensemble Model** (combining MLP and CatBoost)

## Dataset:
The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available on Kaggle:

[Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?utm_source)

## Requirements:
To run this project, you will need the following Python libraries:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- CatBoost
- Matplotlib


## Results:

The following models were tested for accuracy, AUC-ROC, and Average Precision:

* **MLP** recorded the highest accuracy of **98.25%**.
* **Ensemble Model** (Soft Voting) achieved the best **AUC-ROC** of **0.9981**.

The models were evaluated on a test set with 20% of the data (stratified to maintain the class balance).

```

