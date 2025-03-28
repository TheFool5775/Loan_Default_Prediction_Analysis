# Loan Default Prediction using Machine Learning Models

## Overview
This project aims to predict loan defaults based on various features of loan applicants using machine learning algorithms. By analyzing the dataset, we can identify key factors that contribute to loan defaults and develop predictive models that assist financial institutions in making informed lending decisions.

### Key Features:
- **Data Preprocessing**: The project includes steps for handling missing values, outlier detection, and feature scaling to ensure the data is clean and suitable for modeling.
- **Feature Engineering**: Categorical variables are transformed using one-hot encoding, and new features such as the debt-to-income ratio are created to enhance model performance.
- **Model Training**: Multiple machine learning models are trained, including Logistic Regression, Decision Trees, Random Forests, Gradient Boosting, Support Vector Machines, and K-Nearest Neighbors.
- **Model Evaluation**: The performance of each model is evaluated using accuracy, classification reports, and confusion matrices to determine the best approach for predicting loan defaults.

## Dataset Description
The dataset used in this project is `Loan_Default.csv`, which contains information about loan applicants and their loan statuses. The key features in the dataset include:

- **ID**: Unique identifier for each applicant.
- **Status**: Indicates whether the loan was defaulted (1) or not (0).
- **customer_age**: Age of the applicant.
- **customer_income**: Annual income of the applicant.
- **home_ownership**: Type of home ownership (e.g., OWN, RENT).
- **employment_duration**: Duration of employment in years.
- **loan_intent**: Purpose of the loan (e.g., EDUCATION, PERSONAL).
- **loan_grade**: Grade assigned to the loan based on risk.
- **loan_amnt**: Amount of the loan.
- **loan_int_rate**: Interest rate of the loan.
- **term_years**: Duration of the loan in years.
- **historical_default**: Historical default status of the applicant.
- **cred_hist_length**: Length of credit history in months.

## Installation Steps
To run this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Loan_Default_Prediction.git
   cd Loan_Default_Prediction
