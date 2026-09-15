# Titanic Dataset Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset to improve its data quality and prepare it for further analysis.

The dataset was inspected for missing values, duplicate records, inconsistent formatting, data type issues, and numerical outliers.

## Objectives

- Identify data quality issues
- Handle missing values
- Check and remove duplicate records
- Standardize inconsistent categorical values
- Detect and handle outliers using the IQR method
- Correct data types
- Create a clean dataset for further analysis

## Dataset

The project uses the Titanic passenger dataset containing information such as passenger class, gender, age, family details, fare, cabin, embarkation port, and survival status.

## Data Cleaning Performed

### Missing Values

- Missing `Age` values were replaced using the median.
- Missing `Embarked` values were replaced using the mode.
- Missing `Cabin` values were replaced with `Unknown`.

### Duplicate Records

Duplicate rows were checked and removed if present.

### Data Standardization

Categorical values were standardized to maintain consistent formatting.

### Data Types

Numerical columns were checked and converted to appropriate numerical data types.

### Outlier Detection

Outliers were detected using the Interquartile Range (IQR) method.

Extreme numerical values were capped rather than removed so that valid passenger records were preserved.

## Data Quality Verification

The dataset was checked again after cleaning to verify:

- Missing values
- Duplicate records
- Data types
- Numerical ranges
- Outliers

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Conclusion

The Titanic dataset was successfully cleaned and prepared for further analysis.

The project demonstrates important data-cleaning techniques including missing-value handling, duplicate checking, data standardization, data-type correction, and outlier treatment.