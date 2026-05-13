Loan Risk Prediction Dataset Cleaning

This project focuses on cleaning a Loan Risk Prediction dataset using Python and pandas in Google Colab.

Dataset Information

The dataset contains customer-related information such as :
Age
Income
Loan Amount
Credit Score
Years of Experience
Loan Approval Status


Problems Identified :
The following data quality issues were found in the dataset:
Negative values in the Income column
Negative values in the LoanAmount column
Possible duplicate and missing values were checked


Cleaning Steps Performed :
Imported the dataset using pandas
Checked dataset information using head(), info(), and describe()
Checked missing values using isnull()
Checked duplicate rows using duplicated()
Removed invalid negative values from Income and LoanAmount columns
Verified column data types
Saved the cleaned dataset


Tools Used :
Google Colab
Python
pandas
NumPy


Result

After cleaning :
Invalid negative values were removed
Dataset consistency improved
Total rows changed from 5000 to 4969

The cleaned dataset is now ready for data analysis and machine learning tasks.

Files Included :
loan_risk_prediction_dataset.csv → Original dataset

cleaned_loan_dataset.csv → Cleaned dataset

Loan_Cleaning_Project.ipynb → Google Colab notebook containing the cleaning process
