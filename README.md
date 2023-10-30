# Loan_Prediction_System-in-Python-
This system streamlines loan approval for financial institutions by leveraging machine learning techniques to assess loan eligibility based on applicant data. It handles data preprocessing, feature engineering, and deploys predictive models such as logistic regression, decision trees, and random forests.
# Loan Approval Prediction

This repository contains Python code for predicting loan approval using machine learning with `scikit-learn` and data visualization with `matplotlib` and `seaborn`. The dataset used for this project is provided in an Excel file, "loan.xlsx".

## Dataset Information

The dataset contains information about loan applicants, including details such as gender, marital status, dependents, education, self-employment status, income, loan amount, loan term, credit history, property area, and loan status. The data includes both numerical and categorical features.

### Data Preprocessing

The code performs several data preprocessing steps to prepare the dataset for machine learning:

- Handling missing values by filling them with appropriate values.
- Creating new features, including log transformations of loan amount and total income.
- Encoding categorical variables using Label Encoding.
- Splitting the data into training and testing sets.

### Exploratory Data Analysis (EDA)

The code provides exploratory data analysis by generating various plots to visualize the distribution of data and relationships between different features. It includes bar plots and histograms to show counts and distributions of variables such as gender, marital status, dependents, self-employment, loan amount, and credit history.

### Model Training

The code uses a Support Vector Machine (SVM) classifier from scikit-learn to build a machine learning model for loan approval prediction. It splits the data into training and testing sets and encodes categorical variables to prepare the data for training the model.


