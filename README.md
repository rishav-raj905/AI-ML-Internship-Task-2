# AI/ML Internship – Task 2

## Employee Attrition Prediction and Data Preprocessing

This project focuses on preprocessing and predicting employee attrition using the IBM HR Analytics Employee Attrition dataset.

## Dataset

- Records: 1470
- Features: 35
- Target variable: Attrition

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value checking
- Duplicate checking
- Data cleaning
- Categorical feature encoding using OneHotEncoder
- Numerical feature scaling using StandardScaler
- Reusable preprocessing pipeline using ColumnTransformer and Pipeline

## Machine Learning Model

A machine learning classification model was trained to predict whether an employee is likely to leave the organization.

### Model Accuracy

**87.41%**

## Saved Files

- `02_data_preprocessing.ipynb`
- `employee_attrition_clean.csv`
- `preprocessor.pkl`
- `attrition_model.pkl`
- `scaler.pkl`
- `Attrition_Final_Model.pkl`
- `Preprocessing_Report.pdf`

## Preprocessing Pipeline

The preprocessing pipeline was saved as:

`preprocessor.pkl`

The saved pipeline was also tested on an unseen employee sample.

## Project Conclusion

The employee attrition prediction model was successfully developed and the preprocessing workflow was converted into a reusable pipeline.
