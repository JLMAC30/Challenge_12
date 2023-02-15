# Challenge_12
Credit Risk Application
Credit Risk Analysis
In this project, we build and evaluate machine learning models for credit risk analysis. The goal is to identify the creditworthiness of borrowers using historical lending data from a peer-to-peer lending services company.

Background
Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this project, we use various techniques to train and evaluate models with imbalanced classes. We use the imbalanced-learn library to resample the dataset and build a logistic regression model.

Dataset
The dataset contains information about loans, such as loan amount, interest rate, term, credit score, and others. The target variable is the loan status, which can be either "low risk" or "high risk". The dataset is imbalanced, with 68,470 low-risk loans and only 347 high-risk loans.

Prerequisites
To run this project, you need to install the following packages:

numpy
pandas
scikit-learn
imbalanced-learn
Installation
To install the packages, you can run the following command:

Copy code
pip install numpy pandas scikit-learn imbalanced-learn
Files
The project contains the following files:

credit_risk_resampling.ipynb: Jupyter notebook with the code for the resampled data logistic regression model.
credit_risk_ensemble.ipynb: Jupyter notebook with the code for the ensemble learning model.
Resources: a folder with the CSV file containing the dataset.
Running the code
You can run the Jupyter notebooks by opening them in JupyterLab or Jupyter Notebook and running each cell. Make sure you have the dataset file in the "Resources" folder.

Results
We build two machine learning models for credit risk analysis: a logistic regression model with resampled data and an ensemble learning model.

The logistic regression model with resampled data has an accuracy of 0.99, a precision of 100% for low-risk loans and 0.85% for high-risk loans, and a recall of 99% for low-risk loans and 0.91% for high-risk loans. This model is a good option when the priority is to reduce the number of false positives (i.e., healthy loans that are misclassified as high-risk loans).

The ensemble learning model has an accuracy of 0.93, a precision of 99% for low-risk loans and 9% for high-risk loans, and a recall of 91% for low-risk loans and 21% for high-risk loans. This model is a good option when the priority is to reduce the number of false negatives (i.e., high-risk loans that are misclassified as healthy loans).

Authors
This project was created by [Your Name].

License
This project is licensed under the MIT License.
