🏦 Loan Default Prediction

A machine learning project that predicts whether a borrower will default on a loan based on financial, demographic, and credit-related features.
This project helps financial institutions make data-driven lending decisions, reduce risk, and automate loan evaluation.

📘 About the Project

This project uses machine learning to classify loan applicants into:

0 → No Default

1 → Default

The model analyzes factors such as income, credit score, employment details, loan amount, and more to identify high-risk borrowers.

📊 Dataset Information

The dataset contains the following columns:

Feature Name	Description 
 
LoanID	Unique ID for each loan application

Age	Applicant’s age

Income	Monthly or annual income

LoanAmount	Total loan amount requested

CreditScore	Credit history score

MonthsEmployed	Total months the applicant has been employed

NumCreditLines	Number of credit lines the applicant holds

InterestRate	Loan interest rate

LoanTerm	Duration of the loan (months/years)

DTIRatio	Debt-to-income ratio

Education	Education level (High School, Graduate, etc.)

EmploymentType	Job type (Salaried, Self-employed, etc.)

MaritalStatus	Applicant marital status

HasMortgage	Whether the applicant has an existing mortgage

HasDependents	Number of dependents

LoanPurpose	Reason for taking the loan

HasCoSigner	Whether a co-signer is present

Default	Target Variable (0 = No Default, 1 = Default)


🔄 Project Pipeline
✔ 1. Data Cleaning

Remove duplicates

Handle missing values

Convert data types

✔ 2. Exploratory Data Analysis (EDA)

Visualize distributions

Check correlations

Analyze class imbalance

✔ 3. Preprocessing

Label Encoding / One-Hot Encoding

Feature scaling using StandardScaler

Train-Test split

✔ 4. Handle Class Imbalance

Applied SMOTE to oversample minority class (Default = 1)

✔ 5. Model Training

Models used:

Logistic Regression

Random Forest

Gradient Boosting

XGBoost (optional)

✔ 6. Model Evaluation

Metrics used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📈 Results

Accuracy: 0.68
Precision: 0.68
Recall: 0.22
F1-score: 0.33


👨‍💻 Author

Shubham Raut
Data Scientist / Machine Learning Developer
