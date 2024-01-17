# HR_Data_Analysis_SQL

## Project Overview

In this project, I created and structured a database named `data` to manage HR-related information. The primary table, `hrdata`, captures details such as employee demographics, attrition status, and job satisfaction.

## Key Insights

1. **Employee Count:**
   - The total number of employees is calculated using `SELECT SUM(employee_count) AS Employee_Count FROM hrdata;`.

2. **Attrition Analysis:**
   - Attrition count and rate were explored, shedding light on the workforce's turnover using queries like `SELECT COUNT(attrition) FROM hrdata WHERE attrition='Yes';`.
   - The attrition rate, presented as a percentage, provides a holistic view.

3. **Active Employees:**
   - The number of active employees was derived by subtracting the attrition count from the total.

4. **Average Age:**
   - The average age of employees was determined using `SELECT ROUND(AVG(age),0) FROM hrdata;`.

5. **Attrition Breakdown:**
   - Attrition patterns were analyzed based on gender and education field.

6. **Department-wise Attrition:**
   - A detailed examination of attrition rates across different departments was performed.

7. **Employee Distribution by Age Group:**
   - The distribution of employees across various age groups was explored to understand the workforce's composition.

8. **Education Field-wise Attrition:**
   - Attrition trends were investigated based on the education field of employees.

9. **Attrition Rate by Gender for Different Age Groups:**
   - Attrition rates were analyzed by gender within different age bands.

10. **Job Satisfaction Ratings:**
    - The `crosstab` function was employed to display job satisfaction ratings across various job roles.

## Important Note:
- Ensure that the PostgreSQL `tablefunc` extension is activated to run the final query successfully.
- These insights provide valuable information for HR decision-making and strategic planning, facilitating a deeper understanding of workforce dynamics.
