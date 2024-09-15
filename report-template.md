Credit Risk Classification Report
Overview
In this project, we built a model to predict whether loans are high-risk or healthy. The goal was to understand if we could accurately classify loans based on various financial details.

What We Analyzed
We used data from a lending company, which included:

Loan Size: The amount borrowed.
Interest Rate: The cost of borrowing.
Borrower Income: How much the borrower earns.
Debt-to-Income Ratio: How much debt the borrower has compared to their income.
Number of Accounts: How many accounts the borrower has.
Derogatory Marks: Any negative marks on the borrower’s credit report.
Total Debt: The borrower’s total debt.
Loan Status: Whether the loan is high-risk (1) or healthy (0).
How We Did It
Preparing the Data:

We loaded the data and checked its details.
We separated the data into features (information about the loans) and labels (whether the loan is high-risk or healthy).
We split the data into two parts: one for training the model and one for testing it.
Training the Model:

We used a logistic regression model to learn from the training data.
Testing the Model:

We used the model to make predictions on the test data.
We then checked how well the model did by looking at its confusion matrix and classification report.
Results
Logistic Regression Model
Accuracy: The model is 99% accurate overall.
Healthy Loans (0):
Precision: Perfect at 100%. The model rarely makes mistakes identifying healthy loans.
Recall: 99%. The model is very good at finding healthy loans.
High-Risk Loans (1):
Precision: 86%. The model sometimes mistakenly labels healthy loans as high-risk.
Recall: 94%. The model is very good at identifying high-risk loans.
Summary
Our logistic regression model works really well for predicting both healthy and high-risk loans:

Performance: It correctly classifies loans 99% of the time.
Healthy Loans: It has a perfect precision and very high recall, meaning it almost never misclassifies a healthy loan.
High-Risk Loans: It identifies most high-risk loans accurately, though it occasionally mistakes some healthy loans for high-risk.
Recommendation
We recommend using this model because it is highly accurate and reliable for distinguishing between healthy and high-risk loans. Despite a minor trade-off in precision for high-risk loans, the model's overall performance is strong and effective for our needs.

