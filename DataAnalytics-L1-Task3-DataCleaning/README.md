# Titanic Dataset Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset to improve its data quality and prepare it for further analysis.

## Objectives

- Identify data quality issues
- Handle missing values
- Check and remove duplicate records
- Standardize inconsistent categorical values
- Detect and handle outliers using the IQR method
- Correct data types
- Create a clean dataset for further analysis

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

Outliers were detected using the Interquartile Range (IQR) method and extreme values were capped to preserve valid records.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Conclusion

The Titanic dataset was successfully cleaned and prepared for further analysis. Missing values, duplicates, formatting inconsistencies, data types, and numerical outliers were addressed.
