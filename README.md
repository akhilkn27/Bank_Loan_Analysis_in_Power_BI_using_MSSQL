# Bank Loan Analysis in Power BI using MSSQL
This project analyses bank loan data, including loan issue date, status, payment date, annual income, loan amount, and payment type.

<b>1. Raw Data</b>
- Data Source: Imported raw data from an Excel file.
  
- Database Import: Loaded the data into Microsoft SQL Server (MSSQL) for structured storage and efficient querying.
  
- Power BI Connection: Established a connection to the MSSQL database using Power BI’s import query feature.

![image](https://github.com/user-attachments/assets/abb5ecbe-f901-410d-bb64-e06aa6e1cdf5)

<b>2. Data Cleaning and Preparation</b>
- Null Values: Identified and removed rows with NULL values to ensure data completeness.
- Duplicates: Detected and eliminated duplicate records to maintain data integrity.
- Data Types: Verified and corrected data types to ensure consistency and accuracy during analysis.

  ![image](https://github.com/user-attachments/assets/87f1720b-63aa-4f2c-ad1d-c1e01b654a44)

<b>3. Business Operations Analysis</b>
- Total Loan Applicants: Counted the total number of loan applicants.
- Funded Amount: Summarized the total amount funded to loan applicants.
- Amount Received: Calculated the total amount received from loan repayments.
- Average Interest Rate: Computed the average interest rate across all loans.
- Average Debt-to-Income Ratio (DTI): Determined the average DTI ratio to assess borrowers' financial health.
- Loan Status: Analyzed the current status of each loan (e.g., active, paid off, defaulted).

  ![image](https://github.com/user-attachments/assets/ef168154-1250-49e1-910e-6ac0c9daa023)

<b>4. Data Visualization and Insights</b>
- Calendar Slicers: Implemented calendar slicers for dynamic date-based filtering and analysis.
- Good Loans vs. Bad Loans:
    - Visualization: Created visual representations to compare the proportion of good loans (repaid on time) versus bad loans (defaulted or delinquent).
    - Monthly Analysis: Analyzed the number of loan applicants on a monthly basis to identify trends and patterns.
    - State-wise Analysis: Conducted a geographic analysis to visualize the distribution of loan applicants across different states.
    - Term-wise Analysis: Examined loan applications based on the term length (e.g., 12 months, 36 months, 60 months).
    - Loan Type Analysis: Categorized and analyzed loan applications based on the type of payment (e.g., fixed, variable).

      ![image](https://github.com/user-attachments/assets/3d0e1b3a-b3c0-4c71-8ec9-448b7ff159e7)

![image](https://github.com/user-attachments/assets/49bd5539-992f-4bea-ac25-797fd26c817f)

![image](https://github.com/user-attachments/assets/79009323-f190-45be-aaf5-95e90cdb4b6b)

<b>5. Project Deliverables</b>
- Power BI Dashboard: Developed an interactive Power BI dashboard featuring:
- Calendar slicers for date range selection.
- Comparative charts of good loans vs. bad loans.
- Monthly, state-wise, and term-wise analysis visualizations.
- Loan type distribution charts.
  

You can easily expand and change this project to suit your own research needs. If you have any suggestions / questions let me know.

