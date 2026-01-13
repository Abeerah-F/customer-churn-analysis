# Customer Churn Analysis

## Objective
Analyze customer behavior data to identify key drivers of customer churn and build a baseline predictive model to flag customers at high risk of leaving.

## Dataset
Telco Customer Churn dataset containing customer demographics, service subscriptions, contract types, and billing information.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Project Structure
- data/: Raw and processed datasets
- notebooks/: Jupyter notebooks for analysis

## Workflow
- Data cleaning and type correction
- Exploratory data analysis to uncover churn drivers
- Feature encoding and baseline modeling
- Model evaluation and interpretation

## Key Insights
- Month-to-month contracts exhibit significantly higher churn rates
- Customers with shorter tenure are more likely to churn
- Higher monthly charges correlate with increased churn risk


## Machine Learning
A baseline Logistic Regression model was built to predict churn.
Evaluation using accuracy, confusion matrix, and classification report showed:
- Strong performance in identifying non-churn customers
- Reasonable recall for churned customers

This model serves as a foundation for future feature engineering and advanced modeling. 
