Dream Housing Finance – Loan Eligibility EDA

1. Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a Dream Housing Finance loan application dataset.

The objective is to understand loan approval patterns, identify factors associated with loan eligibility, and generate useful insights that can support better loan assessment decisions.

2. Business Problem

Financial institutions need to understand the factors that influence loan approval decisions.

This analysis explores questions such as:

- What proportion of loan applications are approved and rejected?
- Does credit history influence loan approval?
- How do applicant characteristics relate to approval outcomes?
- Does property location show differences in loan approval patterns?
- Are applicant income and loan amount useful indicators?

3. Dataset Description

- Dataset: Dream Housing Finance Loan Prediction
- Records: 614
- Attributes: 13
- Target Variable: Loan_Status
- Target Values: Y (Approved), N (Rejected)

Each row represents one loan application.

4. Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

5. Data Cleaning

The dataset was inspected for missing values and data quality issues.

The following missing-value treatments were performed:

- Gender: Male
- Married: Yes
- Dependents: 0
- Self_Employed: No
- Loan_Amount_Term: 360
- Credit_History: 1.0
- LoanAmount: Median value (128)

After cleaning, all 614 records had complete values across the 13 columns.

6. Exploratory Data Analysis

The analysis included:

- Univariate analysis of individual variables.
- Bivariate analysis to compare applicant attributes with loan status.
- Categorical variable comparisons.
- Numerical variable comparisons.
- Distribution analysis and visualisations.
- Correlation analysis.

7. Key Findings

- Loan approval: 422 applications were approved (approximately 68.7%), while 192 were rejected (approximately 31.3%).
- Credit history: Applicants with a positive credit history had an approval rate of approximately 79.58%, compared with 7.87% for applicants without one.
- Property area: Semiurban applicants had the highest approval rate among the three property-area categories, at approximately 76.82%.
- Marital status: Married applicants had an approval rate of approximately 71.61%, compared with 62.91% for unmarried applicants.
- Gender: Approval rates were relatively close between male and female applicants, suggesting gender alone was not a major differentiator in this dataset.

8. Conclusion

Credit history showed the strongest association with loan approval in this dataset. Property area and marital status also showed differences in approval patterns.

Applicant income and loan amount should be considered alongside other factors rather than used independently to explain approval outcomes.

These findings describe patterns in the available dataset and do not establish causation.

9. Project Files

- "Dream_Housing_Finance_EDA.ipynb" – Jupyter Notebook containing the Python analysis and visualisations.
- Original CSV dataset – Source data used for the analysis.

10. How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries: pandas, numpy, matplotlib, and seaborn.
4. Open "Dream_Housing_Finance_EDA.ipynb".
5. Make sure the CSV filename and file path in the notebook match the downloaded dataset.
6. Run the notebook cells.

11. Author

Name: Vibin R
Project: Dream Housing Finance – Loan Eligibility EDA
Field: Data Analytics
