Problem Statement:-

This project aims to analyze student data for Degree and Diploma programs across various institutions, likely in an educational setting. The project focuses on understanding student demographics, and academic performance, and identifying specific groups of students based on pre-defined criteria.

Data Analysis Process
The provided data likely resides in an Excel file named pp5.xlsx. The analysis process would involve utilizing Excel functions to extract insights from the dataset.
Here's a breakdown of the steps involved in each exercise:

Gender Ratio:
Data Filtering: Filter the data based on "Degree" and "Diploma" programs separately. For Diploma programs, exclude data from "Meerabai" and "Kasturba" campuses.
COUNTIFS Function: Use the COUNTIFS function to count the number of male and female students in each program.
Calculation: Calculate the gender ratio by dividing the number of female students by the number of male students.

Age Brackets:
Data Filtering: Filter the data based on all combinations of "Degree/Diploma" and "Government/Private".
FREQUENCY Function: Utilize the FREQUENCY function to categorize students into the specified age brackets.

Stellar Diploma Students:
Data Filtering: Filter data for "Diploma" students.
Multiple Criteria Filtering: Apply criteria using IF statements within a COUNTIFS function to identify "stellar" students based on 10th marks, 12th marks, and CET rank.
Grouping: Group the count of "stellar" students by Diploma program and school type.

Total 10th Marks (Scenario 1):

Data Filtering & Criteria: Apply the criteria mentioned using nested IF statements combined with SUMIFS function to sum 10th marks of Diploma students meeting either of the conditions: (age>21 AND 12th marks<50%) OR (age<20 AND school type="Government").
Total 10th Marks (Scenario 2):

Data Filtering & Criteria: Similar to Exercise 4, use nested IF statements and SUMIFS to sum 10th marks of students meeting the criteria: (Diploma AND Government) OR ((age<16 OR (17<=age<=20)) AND (Meerabai OR Kasturba)).

Insights (Potential)
Based on the analysis, the project could reveal insights like:
Gender Distribution: Identifying programs with significant gender disparity.
Age Demographics: Understanding the age distribution of students across different programs and institution types.
High-Achieving Students: Recognizing the proportion of "stellar" students in each Diploma program and school type, potentially highlighting effective teaching methodologies or student characteristics.
Targeted Interventions: Identifying students who might require additional support based on age, academic performance, or other factors. This could be useful for designing targeted interventions or support programs.
By analyzing the provided data, this project aims to provide a comprehensive understanding of student characteristics and performance in Degree and Diploma programs. The insights gained can be utilized by educational institutions for strategic planning, resource allocation, and improving educational outcomes.
