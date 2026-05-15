# Employee Turnover Prediction Project

This project aims to predict employee turnover using a dataset of various employee metrics and attributes. By understanding which factors lead to turnover, an organization can take proactive steps to improve employee retention.

## Features
The model is built using a dataset (`employee_turnover.csv`) that includes the following features:
- **Job Satisfaction**: Employee's reported satisfaction level.
- **Performance Rating**: Performance evaluation score.
- **Years At Company**: Tenure of the employee within the company.
- **Work Life Balance**: Rating of the employee's work-life balance.
- **Distance From Home**: Proximity of the employee's home to the workplace.
- **Monthly Income**: Employee's salary/income.
- **Education Level**: Highest education level achieved.
- **Age**: Employee's age.
- **Num Companies Worked**: Number of previous employers.
- **Employee Role**: The role or title of the employee.
- **Annual Bonus**: Bonus amount received.
- **Training Hours**: Hours spent on training and development.
- **Department**: The department the employee works in.

## Project Structure
- `emmployer_turnover.ipynb`: Jupyter Notebook containing the data exploration, preprocessing, and model training (Logistic Regression).
- `employee_turnover.csv`: The dataset used for training the model.

## Model
The project uses a **Logistic Regression** model from `scikit-learn` to classify whether an employee is likely to leave the company (Turnover = 1) or stay (Turnover = 0).
