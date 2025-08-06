
# Task 1: Data Cleaning & Preprocessing (Elevate Internship)

## Objective
Perform data cleaning and preprocessing using Python on Titanic dataset.

## Steps Followed
1. Loaded dataset and explored basic info.
2. Handled missing values (mean/median/mode imputation).
3. Encoded categorical features using one-hot and label encoding.
4. Normalized/standardized numerical features.
5. Detected and removed outliers using boxplots (IQR method).
6. Saved cleaned dataset.

## Files Included
- `task_1_data_preprocessing.ipynb` (main notebook)
- `task_1_script.py` (Python script version)
- `titanic_dataset.csv` (sample dataset)
- `titanic_cleaned.csv` (final cleaned dataset)
- `screenshots/` (if required)

## Interview Questions & Answers
1. **Types of missing data**: MCAR, MAR, MNAR.
2. **Handling categorical variables**: One-hot encoding, label encoding, ordinal encoding.
3. **Normalization vs Standardization**: Normalization rescales to [0,1], standardization rescales to mean=0, std=1.
4. **Outlier detection**: Boxplot, IQR method, z-score.
5. **Importance of preprocessing**: Improves model performance, prevents bias, handles scale differences.
6. **One-hot vs Label encoding**: One-hot creates dummy variables, label encoding assigns numeric codes.
7. **Handling data imbalance**: Oversampling, undersampling, SMOTE, class weights.
8. **Effect of preprocessing**: It significantly improves model accuracy & stability.

## Usage
Open notebook, run all cells, or execute `python task_1_script.py`.

---
