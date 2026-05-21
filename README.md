# Lab4

# Data Preprocessing and PCA Analysis

## Overview
This project focuses on data preprocessing techniques using a student performance dataset. The tasks include identifying data quality issues, handling missing values, detecting outliers, normalizing data, and applying PCA.

## Dataset Features
- Gender
- StudyHours
- Attendance
- PreviousGrade
- FinalGrade

## Tasks Performed

### Task 1: Identify Data Quality Issues
- Checked data types
- Detected missing values
- Generated descriptive statistics

### Task 2: Handle Missing Values
- Applied median imputation strategy to fill missing values

### Task 3: Detect and Handle Outliers
- Used the IQR method to detect outliers
- Removed rows containing extreme values

### Task 4: Normalize Numerical Features
Applied:
- Min-Max Normalization
- Z-score Standardization

### Task 5: Principal Component Analysis (PCA)
- Checked feature correlations
- Applied PCA with 2 components
- Analyzed explained variance ratio

## Libraries Used
- pandas
- numpy
- scikit-learn

## Conclusion
The preprocessing steps improved data quality by handling missing values and outliers. Feature normalization prepared the dataset for machine learning tasks, while PCA reduced dimensionality and preserved most of the dataset variance.
