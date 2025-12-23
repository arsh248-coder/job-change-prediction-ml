# Job Change Prediction using Machine Learning

This project builds an end-to-end machine learning pipeline to predict whether
a candidate is likely to change jobs based on demographic, education, and
employment-related features.

The goal is to understand which factors influence job mobility and to evaluate
the performance of different machine learning models on structured data.

---

## Dataset
The dataset contains anonymized candidate information including:
- Education level
- Years of experience
- Company size and type
- Training hours
- Gender and enrollment status

The target variable indicates whether the candidate is actively looking for a
new job.

---

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Project Workflow
1. Data loading and inspection
2. Data cleaning and handling missing values
3. Encoding categorical features
4. Feature scaling
5. Model training and evaluation
6. Prediction generation on unseen data

---

## Models Used
- Logistic Regression

Model performance was evaluated using accuracy, precision, recall, and F1-score.

---

## Results
- The model achieved reasonable baseline performance on the validation set
- Features related to experience, education, and company characteristics
  showed strong influence on job change prediction

---

## Files in This Repository
- `main.ipynb` – complete machine learning pipeline
- `aug_train.csv` – training dataset
- `aug_test.csv` – test dataset
- `final_predictions.csv` – model predictions
- `sample_submission.csv` – reference output format

---

## How to Run
1. Clone this repository
2. Install required dependencies
3. Open `main.ipynb` in Jupyter Notebook
4. Run the cells sequentially

