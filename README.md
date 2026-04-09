# Employee-Attrition-Analysis
This project analyzes employee data to identify factors driving attrition. After preprocessing and exploration, a Random Forest model was built to predict employees likely to leave. Insights show income, overtime, and job role significantly influence turnover, supporting better HR decisions.

Objective
Identify key factors influencing employee attrition
Analyze employee data to uncover trends and patterns
Build a predictive model to classify employees at risk of leaving

Dataset

The dataset contains employee-related information such as:

Age
Job Role
Monthly Income
Years at Company
Overtime
Job Satisfaction
Attrition (Target Variable)

Tools and Technologies
Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
Google Colab


Project Workflow
1. Data Preprocessing
Loaded and inspected dataset
Handled categorical variables using encoding
Converted target variable (Attrition) into binary format
2. Exploratory Data Analysis (EDA)
Visualized employee distribution across different features
Identified patterns related to attrition
Examined relationships between income, job role, and attrition
3. Feature Engineering
Converted categorical variables using one-hot encoding
Selected relevant features for model training
4. Model Building
Split dataset into training and testing sets
Trained a Random Forest Classifier
5. Model Evaluation
Evaluated performance using:
Accuracy score
Confusion matrix
Classification report

Key Insights
Employees with lower monthly income showed higher attrition rates
Overtime is strongly associated with employee turnover
Certain job roles experience higher attrition than others
Years at company influences likelihood of leaving

Model Performance

The model was able to classify employee attrition with reasonable accuracy and can be used as a decision-support tool for HR teams.

How to Run the Project
Clone the repository

Install dependencies:

pip install -r requirements.txt
Run the notebook or Python script



Future Improvements
Hyperparameter tuning for better model performance
Deploy model as a web application (Streamlit)
Add more advanced models (XGBoost, Logistic Regression)
Integrate real-time prediction system
