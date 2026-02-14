This project implements a structured data cleaning process for a large real-world dataset.
Steps Performed
Converted age and income to numeric types
Parsed signup_time as datetime (UTC)
Imputed missing values using median
Created missing indicators (age_missing, income_missing)
Capped income at the 99th percentile to reduce outlier impact
Standardized city values (trim + lowercase)
Output
Cleaned dataset exported as:
cleaned_dataset.csv
