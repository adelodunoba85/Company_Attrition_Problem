# Company_Attrition_Problem

During my internship at TakenMind, I had the opportunity to work on a significant data science project aimed at helping Company X control employee attrition. The main objective of the project was to understand the types of employees leaving the company and to develop a predictive model to determine which employees were likely to leave next. To achieve this, I worked with two sets of data: one containing information about existing employees and another containing data about employees who had left the company. The dataset included various attributes for each employee, including: 
satisfaction level, 
last evaluation, 
number of projects,
average monthly hours, 
time spent at the company,
work accident history, 
promotion history, 
department and 
salary.

# Analysis and Findings

I started the project by performing exploratory data analysis (EDA) on the provided datasets. This involved data cleaning, visualization, and statistical analysis to gain insights into the factors contributing to employee attrition.

# Analysis of Employees Who Have Left

In the analysis of employees who had left the company, I used a rule-based approach to make inferences about which employees were likely to leave. This approach involved setting specific criteria based on the provided attributes and assigning a "Remark" category to each employee. The resulting distribution was as follows:

Category 1: This category indicated that an employee was likely to leave the company, and it was found to have a count of 455 employees.
Category 0: This category indicated that an employee was not likely to leave the company, and it was found to have a count of 2 employees.
These findings suggested that the majority of employees in the dataset who had left the company were indeed classified as likely to leave according to the inferred criteria (Category 1). However, it was important to note that the small count in Category 0 indicated that very few employees were classified as not likely to leave based on the same criteria. This validation process underscored the potential accuracy of the inferences made through the rule-based approach for employees who had left the company.

#  Analysis of Existing Employees

Next, I applied the same rule-based approach to analyze existing employees. The distribution of the "Remark" variable for existing employees was as follows:

Category 1: This category indicated that an employee was likely to leave the company and was found to have a count of 388 employees.
Category 0: This category indicated that an employee was not likely to leave the company and was found to have a count of 68 employees.
These findings provided insights into the classification of existing employees based on the inferred criteria:

A significant majority of existing employees (388 employees) were classified as likely to leave according to the same criteria applied to employees who had left the company.
There was a presence of employees (68 employees) classified as not likely to leave (Category 0) based on the same criteria.
This outcome highlighted the potential accuracy of the inferences made through the rule-based approach for existing employees, suggesting that a substantial number of them were also classified as likely to leave the company.
