Credit Risk Classification
Overview
This project involves building a logistic regression model to classify loan risk based on historical lending data. The goal is to predict the creditworthiness of borrowers by analyzing various features such as loan size, interest rate, borrower income, and more.

Data
The dataset used in this project is from a peer-to-peer lending services company, containing information on historical lending activity. The data includes the following columns:

loan_size
interest_rate
borrower_income
debt_to_income
num_of_accounts
derogatory_marks
total_debt
loan_status (Target variable, where 0 indicates a healthy loan and 1 indicates a high-risk loan)
Instructions
Set Up the Environment:

Clone the repository to your local machine.
Install necessary packages if you haven't already (e.g., pandas, numpy, scikit-learn).
Load the Data:

Read the lending_data.csv file into a Pandas DataFrame.
Prepare the Data:

Separate the data into features (X) and labels (y).
Split the data into training and testing sets using train_test_split.
Train the Model:

Instantiate and fit a logistic regression model using the training data.
Evaluate the Model:

Make predictions on the testing data.
Generate and review the confusion matrix.
Print the classification report.
Results
The logistic regression model demonstrates strong performance:

Prediction of Healthy Loans (0): The model shows perfect precision (1.00) and high recall (0.99), accurately identifying healthy loans with very few errors.

Prediction of High-Risk Loans (1): The model has good precision (0.86) and recall (0.94), effectively identifying most high-risk loans, although some healthy loans are occasionally misclassified. The F1-score of 0.90 indicates a solid balance between precision and recall.

Overall, the model achieves an impressive accuracy of 99%, reflecting its effectiveness in distinguishing between healthy and high-risk loans. The trade-off in precision for high-risk loans is expected due to the imbalance in the dataset.

Conclusion
The logistic regression model is highly effective for predicting loan risk, providing valuable insights into borrower creditworthiness. Despite a slight trade-off in precision for high-risk loans, the model's high accuracy and balanced performance make it a robust tool for credit risk classification.