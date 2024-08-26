A repository featuring powerbi portfolio project


# HR ANALYTICS DASHBOARD

# Project Objective:

Help an organization to improve employee performance and improve employee retention (reduce attrition) by creating a HR Analytics dashboard.

# Dashboard Setup

1. Import Data into a Power BI Desktop, dataset is a csv file.
2. Open power query editor and in transform data tab while loading data, check for "duplicate values", "null values", and "unwanted column/s to remove".
3. It was observed that in none of the columns errors & empty values were present except columns named 'YearswithCurrManager'and 'EmpID'.
4. Removed irrelevant column/s, duplicates, and any null values that were present during data cleaning and processing.

# Dashboard KPIs

1. Created 6 separate key performance indicators (KPIs) that are the main factors driving employees to leave the organisation.
   (KPIs created were Employee Count, Attrition Count, Attrition Rate, Avg of age, salary and years) 
2. Created a new column named 'Attrition Count' under  transform data using the  "Add Conditional Column"
3. Under the New Measure option, added a new field to calculate the 'Attrition Rate' based on the attrition count. The metric is known as the Attrition Rate, and it is determined using the following formula:
            ***AttritionRate = SUM(HR_Analytics[AttritionCount]) / SUM(HR_Analytics[EmployeeCount])***
4. Using the above-mentioned metric, a new kpi named 'Attrition Rate' was developed by converting it to a percentage value.
5. Finally, using the 'avg' function, calculated the average of salary, years, and age.

# Visualization Charts

1. Six different visualisations were built based on previously created KPIs.
2. Using a Donut chart, developed a 'Attrition by Education' chart, which mostly shows the educational qualifications of employees leaving the organisation.
3. Using a Stacked Column chart, developed a 'Attrition by Age' which mostly shows about the different age groups of employees leaving the organisation.
4. Using a stacked bar chart, created a 'Attrition by jobrole' and 'Attrition by salary' charts which shows about top 4 jobroles by attrition and salary information( salaryslab) of the employees who are leaving the company.
5. Using a area chart, created a 'Attrition by Years' which shows about number of years that an employee was working in the company before leaving.
6. Using a matrix, created a 'job satisfaction' matrix that depicts the levels of employee evaluations on various job positions.
7. Also, created an 'Attrition by gender' based on attrition count & genders.
8. Finally, slicers (visual filters) were added for different departments mainly 'Human Resources' , 'Sales' and 'Research & Development'.

# Findings from the report

1. Total Employee count - 1.413K
2. Total Attrition Count - 210
3. Attrition Rate - 14.9%
4. Avg Age - 38 years
5. Avg salary - 6.7K
6. Avg years - 7.2 years
7. Attrition by gender: Total Male counts - 111 , Total Female counts - 53

![image](https://github.com/CHINMAYI-23/HR_Analytics_Dashboard/assets/87280846/168bb555-56c5-483f-a706-022f8d41eb39)



