<h1>Loan Approval Prediction Project</h1>

<h2>Overview</h2> 
This project focuses on building a machine learning model to predict loan approval decisions based on various applicant details. The goal is to analyze patterns in the dataset and create a model that can accurately classify loan applications as approved or not approved. The project achieves an accuracy of 79.8% using a Random Forest classifier and includes techniques to handle missing values in the dataset.

<h2>Features</h2>
Data Preprocessing: Handling missing values by predicting them instead of dropping rows, ensuring minimal data loss.
Feature Engineering: Transforming categorical and numerical variables for better model performance.
Machine Learning Model: Implemented a Random Forest classifier for predicting loan approval with high accuracy.
Evaluation Metrics: Used accuracy score and other metrics for evaluating model performance.

<h2>Dataset</h2>

The dataset contains details about loan applicants, including:
Applicant Income
Co-applicant Income
Loan Amount
Loan Term
Credit History
Property Area
Gender, Marital Status, and more

<h2>Target Variable</h2>
Loan_Status: Indicates whether a loan is approved ('Y') or not ('N').

<h2>Project Workflow</h2>

<h3>Exploratory Data Analysis (EDA):</h3>
Visualized trends and patterns in loan data.
Analyzed relationships between features and loan approval status.

<h3>Data Preprocessing:</h3>
Imputed missing values for critical columns (e.g., Loan Amount, Credit History).
Encoded categorical variables using label encoding and one-hot encoding as needed.

<h3>Model Building:</h3>
Trained a Random Forest Classifier on the processed dataset.
Fine-tuned hyperparameters to improve performance.

<h3>Evaluation:</h3>
Achieved an accuracy of 79.8%.
Identified potential improvements to further enhance the model's prediction power.

<h2>Results</h2>
The model predicts loan approvals with 79.8% accuracy.
Missing values were effectively imputed, reducing data loss and improving prediction reliability.

