
Data Cleaning Pipeline
================================================================================
This project implements a structured data cleaning process for a large real-world dataset.

Steps Performed:
1. Converted age and income to numeric types
2. Parsed signup_time as datetime (UTC)
3. Imputed missing values using median
4. Created missing indicators (age_missing, income_missing)
5. Capped income at the 99th percentile to reduce outlier impact
6. Standardized city values (trim + lowercase)
--------------------------------------------------------------------------------
Output:
- cleaned_dataset.csv
--------------------------------------------------------------------------------
The End!! — with love,
Programmer Deema <3
================================================================================
