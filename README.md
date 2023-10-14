# Loan_Prediction
Based on data provided by consumers while completing an online application form, the company aims to automate (in real time) the loan qualification process. In order to speed up the process of deciding whether or not an applicant qualifies for a loan, it is anticipated that the company will develop machine learning models that can assist in predicting loan approval.

# Objectives 
## This notebook aims to:
•	Analyse customer data provided in data set (EDA)
•	Build various ML models that can predict loan approval

# The machine learning models used in this project are:
•	Logistic Regression
•	K-Nearest Neighbour (KNN)
•	Support Vector Machine (SVM)
•	Naive Bayes
•	Decision Tree
•	Random Forest
•	Gradient Boost
•	Data Set Description 

# There are 13 variables in this data set:
Categorical variables: 8
Continuous variables: 4 and
Variable to accommodate the loan ID: 1.

# The structure of the Data set
•	Loan ID: Loan reference number (unique ID) LP001002; LP001003; ...
•	Gender	: Gender of the applicant (Male or Female) Male; Female
•	Married Applicant: marital status (Married or not married) Married; Not Married
•	Dependents: Number of family members 0; 1; 2; 3+
•	Education Applicant: education/qualification (graduate or not graduate)	Graduate; Under Graduate
•	Self-employed: Applicant employment status (yes for self-employed, no for employed/others) Yes; No
•	Applicant Income: Applicant's monthly salary/income 5849; 4583; ...
•	Co-applicant Income: Additional applicant's monthly salary/income 1508; 2358; ...
•	Loan Amount: Loan amount	128; 66; ...
•	Loan_Amount_Term: The loan's repayment period (in days) 360; 120; ...
•	Credit History: Records of previous credit history (0: bad credit history, 1: good credit history)	0; 1
•	Property Area: The location of property (Rural/Semiurban/Urban) Rural; Semiurban; Urban
•	Loan Status: Status of loan (Y: accepted, N: not accepted) Y; N
