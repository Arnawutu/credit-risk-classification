# credit-risk-classification

Credit Risk Assessment Project

This project involves employing various methodologies to train and evaluate a machine learning model geared towards assessing loan risk. Utilizing a historical dataset from a peer-to-peer lending company, the goal is to construct a model capable of gauging borrower creditworthiness.

Guidelines
The steps for this project are organized into distinct sections:

- Preparing the Data
- Developing a Logistic Regression Model Using Original Data
- Compiling a Credit Risk Evaluation Report

Preparing the Data
Proceed by following these steps in the provided starter code notebook:

- Load the "lending_data.csv" file from the Resources directory into a Pandas DataFrame.
- Generate the target labels (y) from the “loan_status” column and formulate the features (X) DataFrame from the other columns.

**Remember:** In the “loan_status” column, a zero signifies a healthy loan, while a one indicates a high probability of default.

- Divide the dataset into training and test sets using the train_test_split method.

Developing a Logistic Regression Model Using Original Data
Apply your understanding of logistic regression to perform the following tasks:

- Train a logistic regression model using the training data (X_train and y_train).
- Record the model's predictions for the test labels using the test features (X_test) and the trained model.

Assess the model’s performance by:

- Creating a confusion matrix.
- Printing the classification report.
- Address this query: How effectively does the logistic regression model distinguish between 0 (healthy loan) and 1 (high-risk loan) categories?

Compiling a Credit Risk Evaluation Report
Craft a concise report summarizing and analyzing the machine learning models' performance used in this project. This report should be presented as the README.md file in your GitHub repository.

Follow the structure provided in the report template from Starter_Code.zip, ensuring it covers:

- Analysis Overview: Clarify the purpose of the analysis.
- Results: Detail the model's accuracy, precision, and recall scores using bullet points.
- Conclusion: Synthesize the outcomes of the machine learning model. Advocate for or against the model's adoption by the company, supporting your recommendation with reasons.