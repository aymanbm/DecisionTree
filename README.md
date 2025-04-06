# DecisionTree & Random Forest

## Prediction of Valuable Employee Attrition
This project aims to predict employee attrition using Decision Tree and Random Forest algorithms. The objective is to identify the key factors leading to the voluntary departure of valuable employees, enabling HR departments to anticipate and reduce turnover.

## Dataset
The dataset (EmployeeAttrition.csv) includes both numerical and categorical variables describing employees' personal, professional, and organizational characteristics. Comprehensive data preprocessing was conducted, including handling missing values, encoding categorical features, data normalization, and outlier detection using the IQR method.

## Key Features
Age: Age of the employee.

JobRole: Position held within the company.

MonthlyIncome: Monthly salary of the employee.

YearsAtCompany: Number of years the employee has been with the company.

JobSatisfaction: Reported level of job satisfaction.

OverTime: Whether the employee works overtime (Yes/No).

Attrition (Target): Whether the employee left the company (Yes/No).

## Models Used
Decision Tree: Chosen for its interpretability and ability to visualize decision paths.

Random Forest: Used to improve predictive performance and reduce overfitting through ensemble learning.

## Model Evaluation
Model performance was assessed using the following metrics:

Accuracy

Precision & Recall

Confusion Matrix

F1_score
## Installation & Setup

Ensure you have Python installed along with the required libraries.

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

