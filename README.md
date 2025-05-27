# Python

# Capstone Project: Python Fundamentals Data Analysis

# Situation: This capstone project involved analyzing three distinct datasets containing critical information on project details, employee demographics, and designation levels within an organizational context. The project required understanding columns related to project identifiers, employee demographics, and job positions.

# Task: The primary objective was to demonstrate proficiency in Python fundamentals, particularly using the NumPy and Pandas libraries, to perform a series of data cleaning, transformation, and analytical tasks. This included addressing specific challenges such as handling missing values, splitting columns, joining datasets, and applying complex conditional logic to derive actionable insights.

# Action (How I Did This):
I executed a comprehensive data pipeline by writing Python code in an executable file, covering the following key steps:
Data Ingestion & Preparation: Created three distinct Pandas DataFrames from the provided raw data and saved them as .csv files for subsequent tasks.
Missing Value Imputation: Addressed missing values in the 'Cost' column of the 'Project' DataFrame by computing and replacing them with a running average, implemented using a for loop.
Data Transformation: Split the 'Name' column in the 'Employee' DataFrame into 'First Name' and 'LastName', subsequently removing the original 'Name' column.
Data Integration: Joined all three cleaned DataFrames into a single, comprehensive 'Final' DataFrame to facilitate unified analysis.
Feature Engineering & Conditional Logic:
Added a new 'Bonus' column to the 'Final' DataFrame, assigning a 5% bonus based on project cost exclusively to employees who had completed their projects.
Implemented logic to demote designation levels by one for project heads whose projects had a 'Failed' status, and subsequently deleted records of employees whose designation level exceeded 4.
Applied prefixes ("Mr."/"Mrs.") to the 'First Name' column based on gender and then dropped the 'Gender' column.
Promoted the designation level by one for employees whose age was greater than 29 years, utilizing explicit IF conditions.
Aggregation & Reporting: Calculated the total cost of all projects for each employee, saving this summary into a new 'TotalProjCost' DataFrame with 'ID', 'First Name', and 'Total Cost' columns.
Data Filtering: Extracted and printed details for employees whose city names contained the letter "o".
Result (Key Learning Outcomes):
This capstone project served as a direct evaluation of my ability to apply fundamental Python programming skills, particularly using NumPy and Pandas, for real-world data science challenges. It provided a practical understanding of how to approach diverse data manipulation and analysis tasks, assessing my readiness for complex data scenarios. The final deliverable was a .ipynb file containing all code and outputs, meticulously commented for clarity.

# Skills Applied:

Data Cleaning & Preprocessing using Pandas
Handling Missing Values with imputation techniques (running average)
Merging & Joining DataFrames for combining datasets
Using NumPy & Pandas for data manipulation and analysis
Applying Conditional Logic to transform and filter data
Data Aggregation & Grouping
Basic Python Programming Constructs (e.g., loops, conditionals)
