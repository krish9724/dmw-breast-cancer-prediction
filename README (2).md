# Breast Cancer Prediction using Decision Tree and SVM

Data Mining and Warehousing (BTECHCSE230703) - Project, JG University, School of Engineering

**Name:** Gupta Krish | **Enrollment No.:** 2301441007 | **Roll No.:** 1003 | **Branch:** CSE, Division A

## About
Predicts whether a breast tumour is malignant or benign from 30 cell-nucleus measurements.
Two classification algorithms are implemented and compared: **Decision Tree** and **Support Vector Machine (SVM)**.

## Dataset
Breast Cancer Wisconsin (Diagnostic), UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
569 records, 30 numeric attributes (also included here as `breast_cancer_wisconsin.csv`).

## Files
- `DMW_Project_Code_Gupta_Krish_2301441007.ipynb` - notebook (preprocessing, models, evaluation)
- `breast_cancer_wisconsin.csv` - dataset
- `DMW_Project_Report_Gupta_Krish_2301441007.pdf` - project report
- `DMW_Project_Presentation_Gupta_Krish_2301441007.pptx` - presentation

## Run
Open the notebook in Google Colab and choose Runtime > Run all. No extra installation is needed (scikit-learn, pandas, seaborn and matplotlib are preinstalled in Colab).

## Results (test set, 114 records, random_state = 42)
| Model | Accuracy | Precision (malignant) | Recall (malignant) | F1 (malignant) | ROC-AUC |
|---|---|---|---|---|---|
| Decision Tree | 0.8772 | 0.7800 | 0.9286 | 0.8478 | 0.9593 |
| SVM (RBF) | 0.9825 | 0.9762 | 0.9762 | 0.9762 | 0.9977 |

10-fold cross-validation accuracy: SVM 0.9772, Decision Tree 0.9191.
