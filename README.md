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

## Model Training and Testing Overview
In this project, we utilize various machine learning algorithms to predict loan defaults based on applicant features. The model training and testing process involves several key steps:

## Data Preprocessing:

1.**Handling Missing Values**: Missing values in the dataset are addressed using the SimpleImputer. For numerical features, missing values are replaced with the mean of the respective columns, ensuring that no data is lost during the training process.

2.**Encoding Categorical Variables**: Categorical features are transformed into numerical format using one-hot encoding. This process creates binary columns for each category, allowing the models to interpret categorical data effectively.

3.**Feature Scaling**: Numerical features are standardized using StandardScaler, which scales the data to have a mean of 0 and a standard deviation of 1. This step is crucial for algorithms sensitive to the scale of the data, such as Logistic Regression and Support Vector Machines.

## Train-Test Split:

The dataset is split into training and testing sets using train_test_split. Typically, 70% of the data is used for training the models, while 30% is reserved for testing. This split allows us to evaluate the model's performance on unseen data.
## Model Training:

Multiple machine learning models are trained on the training dataset. The models included in this project are:
1.**Decision Tree**: A non-linear model that splits the data based on feature values.

2.**Random Forest**: An ensemble method that combines multiple decision trees to improve accuracy and reduce overfitting.

3.**Gradient Boosting**: Another ensemble technique that builds trees sequentially to minimize errors.

4.**Support Vector Machine (SVM)**: A model that finds the optimal hyperplane to separate classes.

5.**K-Nearest Neighbors (KNN)**: A non-parametric method that classifies based on the majority class of the nearest neighbors.
## Model Evaluation:

After training, each model is evaluated on the testing dataset. The evaluation metrics used include:
Accuracy: The proportion of correctly predicted instances out of the total instances.
Classification Report: A detailed report that includes precision, recall, and F1-score for each class.
Confusion Matrix: A matrix that visualizes the performance of the model by showing true positive, true negative, false positive, and false negative counts.
## Results Visualization:

The accuracies of the different models are visualized using a bar chart, allowing for easy comparison of model performance. By following this structured approach to model training and testing, we aim to build robust predictive models that can effectively identify potential loan defaults based on applicant data.
## Visualizations
The project also includes visualizations to explore the loan default dataset and gain insights into the data. Key visualizations include:

1.**Histograms**: To visualize the distribution of numerical features in the dataset.

2.**Pie Charts for Categorical Variables**: To show the distribution of categories within categorical features.

3.**Pie Chart for Customer Income Distribution**: To visualize the distribution of customer income in binned ranges.

4.**Pie Chart for Loan Classification**: To illustrate the classification of loans into creditworthy and non-creditworthy categories.

5.**Scatter Plots**: To explore relationships between pairs of numerical variables.

6.**Correlation Heatmap**: To visualize the correlation between numerical features in the dataset.

## Conclusion
The visualizations generated from this analysis provide valuable insights into the loan default dataset. They help in understanding the distribution of key features, the relationships between different variables, and the overall characteristics of the customer base. This analysis can serve as a foundation for further modeling and predictive analysis in the context of loan defaults.
