Loan Management System (LMS) --- Loan Portfolio Analysis
Project Overview
This is a Business Analysis case study in the Banking and Financial
Services domain. It explores historical LendingClub loan records to
identify patterns associated with loan outcomes and uses the findings to
suggest reporting and monitoring capabilities for a proposed Loan
Management System (LMS).

Project type: Business Analysis Case Study
Dataset: LendingClub historical loan dataset
Tools: Python, Pandas, NumPy, Matplotlib, Jupyter Notebook
Project Objectives
- Explore historical loan records and understand loan outcomes.
- Compare outcomes across loan grades, terms, DTI groups and
  verification categories.
- Identify portfolio patterns useful for management reporting.
- Suggest data fields and monitoring capabilities for a proposed LMS.
Dataset
The notebook analyses 396,030 records and 27 columns. Fields include
loan amount, term, interest rate, grade, employment length, annual
income, verification status, loan purpose, debt-to-income ratio (DTI)
and loan status.

The original dataset is kept unchanged. A working copy is used for basic
cleaning.
Analysis Performed
1. Loan status distribution
2. Loan amount by loan status
3. Loan purpose distribution
4. Loan grade distribution
5. Loan grade and loan status
6. Average interest rate by grade
7. Employment length distribution
8. Average loan amount by purpose
9. Average loan amount by employment length
10. DTI and loan status
11. Verification status and loan status
12. Loan term and loan status
Key Findings
- The dataset contains 318,357 Fully Paid loans and 77,673
  Charged Off loans.
- Charged-off shares vary across grades, from 6.29% for Grade A to
  47.84% for Grade G.
- Average interest rates increase across grades, from 7.39% for
  Grade A to 25.90% for Grade G.
- Higher DTI groups show a higher charged-off share in this dataset.
- The charged-off share is 15.77% for 36-month loans and 31.94%
  for 60-month loans.
- Debt consolidation and credit card are the most common loan
  purposes.
These are observed historical associations. They do not establish that
any factor caused a loan to be charged off.
Suggested LMS Capabilities
A proposed LMS could support: - Centralised loan and borrower records. -
Tracking loan amount, purpose, grade, interest rate and term. -
Recording applicant income, employment length and DTI. - Verification
status tracking. - Portfolio reports by loan status, grade, term and
other categories. - Management summaries for portfolio monitoring.

These are proposed capabilities, not workflows confirmed by the dataset.
Limitations
The dataset does not provide complete application-stage history,
document-review timestamps, staff assignments, actual instalment payment
records or collections notes. Therefore, this project cannot measure
application turnaround time, missed EMI events or collections
performance.

The analysis is exploratory and uses historical records. Findings should
not be treated as a credit-approval policy or proof of causation.
Repository Contents
- Loan_Management_System_EDA_Simple.ipynb --- notebook containing
  data inspection, basic cleaning and exploratory analysis.
- lending_club_loan_two.csv ---
4. Open Jupyter Notebook and run
   Loan_Management_System_EDA_Simple.ipynb from top to bottom.

