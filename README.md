# Student Performance Analysis & Prediction

## Project Overview

This project analyzes student performance using data analysis and machine learning techniques. The objective is to identify factors associated with students' exam scores and build models to predict academic performance.

## Dataset

The dataset contains information about student study habits, attendance, previous scores, parental involvement, access to resources, extracurricular activities, and other factors.

- Records: 6,607
- Features: 20
- Target Variable: `Exam_Score`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data loading
2. Data cleaning
3. Exploratory Data Analysis (EDA)
4. Data preprocessing
5. Feature engineering
6. Train-test split
7. Machine learning model training
8. Model evaluation
9. Feature importance analysis
10. Final insights

## Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Model Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 0.478 | 1.856 | 0.758 |
| Random Forest | 1.099 | 2.141 | 0.678 |
| Gradient Boosting | 0.815 | 1.978 | 0.725 |

Among the models tested on the test set, Linear Regression produced the lowest MAE and RMSE and the highest R² for this dataset and preprocessing approach.

## Key Findings

Feature importance analysis using Random Forest indicated that:

- Attendance was the most important individual feature.
- Hours Studied was the second most important feature.
- Previous Scores were another important numerical feature.

The analysis shows that attendance, study time, and previous academic performance were strongly associated with predicted exam scores in this dataset.

## Project Structure

```text
Student Performance Analysis/
│
├── data/
│   └── StudentPerformanceFactors.csv
│
├── images/
│
├── notebooks/
│   └── Student_Performance_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore