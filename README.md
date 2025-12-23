# Job Change Prediction using Machine Learning

This project implements an end-to-end machine learning pipeline to predict whether a candidate is likely to change jobs based on demographic, education, and employment-related features.

The objective is to analyze factors influencing job mobility and to compare multiple machine learning models on an imbalanced classification task.

---

## Dataset
The dataset contains anonymized candidate information, including:

- Education level
- Years of experience
- Company size and type
- Training hours
- Gender and enrollment status

The target variable indicates whether a candidate is actively seeking a new job.

---

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Project Workflow
1. Data loading and inspection  
2. Missing value handling and preprocessing  
3. Encoding categorical features  
4. Train/validation split  
5. Model training and evaluation  
6. Model comparison  
7. Final prediction generation using the best model  

---

## Models Used
- Logistic Regression (baseline)
- Random Forest
- XGBoost (final selected model)

---

## Model Performance (Validation Set)

| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------|----------|--------|----------|
| Logistic Regression | 0.77 | 0.59 | 0.29 | 0.38 |
| Random Forest | 0.78 | 0.57 | 0.50 | 0.53 |
| **XGBoost** | **0.80** | **0.60** | **0.58** | **0.59** |

**XGBoost achieved the best overall performance**, particularly improving recall and F1-score on the imbalanced dataset, and was selected as the final model.

---
