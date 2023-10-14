# Loan_Prediction
## Abstract:
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

## Data Set Information:
The information relates to direct marketing initiatives of a Portuguese financial institution. The marketing campaigns were based on phone calls. It was frequently necessary to make multiple contacts with the same client in order to determine whether the product (bank term deposit) would be subscribed ('yes') or not ('no').

## Attribute Information:
# Bank client data:
•	Age (numeric)
•	Job: type of job (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown')
•	Marital: marital status (categorical: 'divorced', 'married', 'single', 'unknown' ; note: 'divorced' means divorced or widowed)
•	Education (categorical: 'basic.4y', 'basic.6y', 'basic.9y', 'high school', 'illiterate', 'professional course', 'university degree', 'unknown')
•	Default: has credit in default? (categorical: 'no', 'yes', 'unknown')
•	Housing: has housing loan? (categorical: 'no', 'yes', 'unknown')
•	Loan: has personal loan? (categorical: 'no', 'yes', 'unknown')

# In connection with contact, social, economic, and campaign-related attributes:
•	Contact: contact communication type (categorical:'cellular','telephone')
•	Month: last contact month of year (categorical: 'jan', 'feb','mar', ..., 'nov', 'dec')
•	Day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
•	Duration: last contact duration, in seconds (numeric). Important
•	note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
•	Campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
•	Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
•	Previous: number of contacts performed before this campaign and for this client (numeric)
•	P outcome: outcome of the previous marketing campaign (categorical: 'failure', 'non-existent', 'success')
•	Emp.var.rate: employment variation rate - quarterly indicator (numeric)
•	Cons.price.idx: Consumer Price Index - Monthly Indicator (Numeric).
•	Cons.conf.idx: consumer confidence index - monthly indicator (numeric)
•	Euribor: Euribor 3-month rate - daily indicator (numeric)
•	Nr. employed: number of employees - quarterly indicator (numeric)

# Output variable (desired target):
•	Y - Has the customer subscribed to a term deposit? (binary: 'yes', 'no')

# Analysis Steps:
•	Attribute information analysis.
•	Machine Learning (Logistic Regression, KNN, SVM, Decision Tree,
•	Random Forest, Naive Bayes)
•	Deep Learning (ANN)
