Sailport Motors Employee Attrition Analysis & Prediction
This project, developed as part of the Google Data Advanced Analytics Capstone on Coursera, focuses on identifying the key drivers of employee attrition at Sailport Motors and developing a predictive model to forecast churn. By analyzing a comprehensive dataset of employee records, this initiative aims to provide actionable insights and recommendations to Human Resources for reducing attrition and optimizing workforce planning.

Project Overview
Sailport Motors is seeking to improve its employee retention and answer the critical question: What is likely to make a Sailport Motors employee leave the company? Employee attrition is a significant challenge for many organizations, leading to increased costs, loss of institutional knowledge, and decreased productivity. This project leverages data analysis and machine learning techniques to understand the underlying factors contributing to employee turnover and to predict which employees are at risk of leaving.

Key Features
Extensive Data Analysis: Processed and analyzed over 2,700 employee records to uncover patterns and trends related to attrition.

Attrition Driver Identification: Utilized Python libraries (Pandas, NumPy, Seaborn) to identify significant factors influencing employee churn, such as department, tenure, performance, and more.

Predictive Modeling: Developed a logistic regression model to predict employee churn, achieving the following performance metrics:

Accuracy: 82%

Precision (weighted average): 79%

Recall (weighted average): 82%

F1-score (weighted average): 80%
The model helps in identifying at-risk employees proactively.

Feature Importance Assessment: Evaluated the impact of various features on the churn prediction, providing insights into which aspects are most critical.

Interactive Data Visualization: Created dynamic Tableau dashboards to visualize attrition trends across different dimensions (e.g., department, tenure, performance), making complex data easily understandable for executives.

Actionable HR Recommendations: Formulated concrete, data-driven recommendations for HR strategies aimed at reducing churn and improving overall workforce stability, including:

Placing a cap on the number of projects employees can work on.

Considering promotions for employees with a minimum of 4 years of tenure, or investigating dissatisfaction among 4-year employees.

Rewarding employees for longer hours or making long hours non-mandatory.

Ensuring clear communication of rules around logged hours and time off expectations.

Conducting company-wide and individual team discussions to address work culture.

Technologies Used
Python:

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Seaborn: For statistical data visualization.

Scikit-learn: For building and evaluating the logistic regression model.

Tableau: For creating interactive dashboards and visualizations.

Project Structure
.
├── data/
│   └── employee_records.csv  # (Example: Raw or processed employee data)
├── notebooks/
│   └── attrition_analysis.ipynb # (Jupyter notebook for data analysis and modeling)
├── tableau_dashboards/
│   └── attrition_dashboard.twbx # (Tableau workbook file)
├── reports/
│   └── Sailport_Motors_Executive_Summary.pdf # (Executive Summary document)
└── README.md

Install Python dependencies:

pip install pandas numpy seaborn scikit-learn

Run the analysis:

Ensure employee data (e.g., employee_records.csv) is placed in the data/ directory.

Open the attrition_analysis.ipynb notebook in a Jupyter environment (e.g., Jupyter Lab, VS Code with Jupyter extension).

Execute the cells to perform data loading, analysis, model training, and evaluation.

Explore Tableau Dashboards:

Open the attrition_dashboard.twbx file using Tableau Desktop to interact with the visualizations.

Results & Impact
The analysis revealed key drivers of attrition specific to Sailport Motors, enabling targeted interventions. The predictive model provides a powerful tool for identifying employees at high risk of leaving, allowing HR to implement retention strategies proactively. The Tableau dashboards offer a clear, executive-level view of attrition trends, facilitating informed decision-making. The delivered recommendations are designed to optimize workforce planning and significantly reduce churn rates at Sailport Motors.
