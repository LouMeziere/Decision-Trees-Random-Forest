# Decision-Trees-Random-Forest

# Description: Predicting Loan Repayment Using Lending Club Data

The objective of this project is to analyze a dataset from LendingClub.com to predict whether borrowers will fully repay their loans. Lending Club serves as a platform connecting borrowers with investors, emphasizing the need for accurate prediction of loan repayment likelihood. We will develop and compare two models, a decision tree and a random forest, to determine which performs better for this dataset. By leveraging borrower characteristics and credit metrics, our goal is to enhance investment decision-making and mitigate risks associated with loan defaults.

# Libraries

scikit-learn, pandas, seaborn, matplotlib

# Table of Contents

1. Load and Inspect the Data
2. Exploratory Data Analysis
3. Data Preprocessing
4. Training and Evaluating a Decision Tree Model
5. Training and Evaluating a Random Forest Model
6. Conclusion


# Dataset Information

You can download the dataset [here](https://www.lendingclub.com/info/download-data.action) or use the provided CSV, which has been cleaned of NA values.

**Column Definitions:**
- `credit.policy`: 1 if the borrower meets LendingClub.com's credit criteria, 0 otherwise.
- `purpose`: Purpose of the loan (e.g., "credit_card", "debt_consolidation", "educational").
- `int.rate`: Interest rate of the loan as a proportion (e.g., 0.11 for 11%).
- `installment`: Monthly payment owed by the borrower if the loan is funded.
- `log.annual.inc`: Natural log of the borrower's annual income.
- `dti`: Debt-to-income ratio (debt amount divided by annual income).
- `fico`: FICO credit score.
- `days.with.cr.line`: Length of time borrower has had a credit line.
- `revol.bal`: Borrower's revolving balance (amount unpaid at end of credit card billing cycle).
- `revol.util`: Revolving line utilization rate (amount of credit used relative to total available).
- `inq.last.6mths`: Number of inquiries by creditors in the last 6 months.
- `delinq.2yrs`: Number of times borrower was 30+ days past due on a payment in the past 2 years.
- `pub.rec`: Number of derogatory public records (e.g., bankruptcy filings, tax liens).
