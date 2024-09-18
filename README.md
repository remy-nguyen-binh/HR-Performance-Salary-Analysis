# Optimizing HR Performance and Compensation Analysis
## Project Overview
For this project, I will analyze a dataset consisting of 1,000 employees, focusing on key human resource metrics such as performance, job satisfaction, salary, and employee turnover. This dataset includes various departments (HR, Sales, Marketing, IT, Finance, and Operations) and contains information on employee performance scores, job satisfaction levels, salaries, and other relevant data points.
## Stakeholder questions
The primary goal of this analysis is to provide insights into two key stakeholder questions:
####  What is the relationship between performance scores and job satisfaction across departments?
Understanding the relationship between performance and job satisfaction is crucial for identifying areas where employee engagement might influence productivity. This analysis will help HR stakeholders determine if high job satisfaction leads to better performance and whether there are any department-specific trends.

## Dataset Overview
The dataset contains the following features:

- Employee ID: Unique identifier for each employee.
- Name: Employee name.
- Department: Department where the employee works.
- Position: Employee job position.
- Salary: Annual salary of the employee.
- Hire Date: Date the employee was hired.
- Performance Score: Performance rating on a scale from 1 to 5.
- Sick Days Taken: Number of sick days taken in the past year.
- Training Hours: Number of hours spent in training.
- Job Satisfaction Score: Job satisfaction rating on a scale from 1 to 5.
- Overtime Hours: Total number of overtime hours worked.
- Turnover Risk: Employee’s likelihood of leaving the company (Low, Medium, High).
- Work Location: Employee's work setting (Remote, On-Site, Hybrid).
- Supervisor ID: Unique identifier for the employee’s supervisor.

## Data Source
You can download the raw excel file [here](https://github.com/remy-nguyen-binh/HR-Performance-Salary-Analysis/blob/main/HRIS_HR_Analyst_Dataset.csv)

## Tool
I am using the Microsoft Excel for this analysi.
## Data Analysis Steps
### Data Cleaning
Remove or handle any missing or erroneous data, ensuring the dataset is complete and ready for analysis.
### Exploratory Data Analysis
### Relationship between performance scores and job satisfaction across departments
After analyzing the pivot table, I found some interesting trends in performance and job satisfaction across departments:

- **Sales Department**: This department has the **highest average performance score** but the **lowest average job satisfaction score**.
- **IT Department**: Conversely, the IT department has the **highest average job satisfaction score** but the **lowest average performance score**.
- **Finance Department**: Similar to Sales, the Finance department shows a **negative correlation** between job satisfaction and performance.
- **IT Department**: Unlike the Sales and Finance departments, the IT department demonstrates a **very strong positive correlation** between job satisfaction and performance.

#### Hypothesis for Correlation in Each Department:

1. **Sales Department (Negative Correlation)**:
   - The high performance scores in Sales might be attributed to **high-pressure environments**, **strict targets**, or **performance-driven incentives**. While this drives productivity, it may lead to **job dissatisfaction** due to stress, burnout, or a lack of work-life balance.
   - Hypothesis: High expectations and pressure for performance could be **lowering job satisfaction**, even though employees are performing well.

2. **IT Department (Positive Correlation)**:
   - In IT, high job satisfaction could stem from a **better work-life balance**, **flexible work arrangements**, or a **positive work culture**. However, this may not directly translate into high performance if there’s a **lack of performance-driven incentives** or **clear productivity targets**.
   - Hypothesis: High job satisfaction in IT, likely from work flexibility or job security, correlates with **improved performance** over time, though the department might lack performance pressure seen in other areas.

3. **Finance Department (Negative Correlation)**:
   - Similar to Sales, Finance might have a **demanding work environment** with stringent deadlines or regulatory pressures. This can negatively impact job satisfaction, even if employees are performing at a high level.
   - Hypothesis: The structured, high-pressure nature of Finance roles might result in **reduced job satisfaction**, despite the need for accuracy and performance.

#### Recommendations for Stakeholders:

1. **Sales Department: Improving Job Satisfaction**
   - **Recommendation**: Implement initiatives aimed at reducing stress and improving work-life balance to boost job satisfaction. Consider offering flexible work hours, wellness programs, or stress management training to create a more supportive environment.
   - **Rationale**: Since the Sales team already performs at a high level, improving job satisfaction could lead to longer-term employee retention and reduce burnout without sacrificing performance.

2. **IT Department: Enhancing Performance**
   - **Recommendation**: Introduce clearer performance metrics and incentives to align the IT department’s high job satisfaction with improved performance. Regular performance reviews, goal-setting workshops, and the introduction of performance bonuses can help motivate employees to excel.
   - **Rationale**: The IT department shows strong job satisfaction, but performance may lag due to a lack of structured goals or performance incentives. Addressing this can help capitalize on their positive work environment.

3. **Finance Department: Balancing Satisfaction and Performance**
   - **Recommendation**: Conduct a survey to identify key drivers of job dissatisfaction in the Finance department, and explore ways to alleviate pressure. Offering time management workshops, flexible deadlines when possible, or additional support could help.
   - **Rationale**: Addressing the high-pressure nature of Finance roles without sacrificing accuracy or performance could boost employee morale, leading to improved long-term engagement and productivity.

4. **Company-Wide: Cross-Departmental Learning**
   - **Recommendation**: Facilitate knowledge-sharing sessions between departments, particularly focusing on how departments with high job satisfaction, like IT, create a positive environment. These best practices can be implemented across other departments such as Sales and Finance.
   - **Rationale**: Understanding what makes employees in IT more satisfied can help adapt similar strategies in other departments, leading to a more balanced approach between performance and job satisfaction across the organization.

5. **Performance Incentives and Recognition**
   - **Recommendation**: Develop a performance recognition and incentive program tailored to the different departmental needs. Recognize both high-performing and highly engaged employees through awards, bonuses, or career development opportunities.
   - **Rationale**: A well-structured incentive system encourages high performance while simultaneously fostering job satisfaction across departments.

## Presentation
You can download the raw excel file [here](https://github.com/remy-nguyen-binh/HR-Performance-Salary-Analysis/blob/main/PowerPoint%20Presentation%20-%20HR%20Performance%20and%20Job%20Satisfaction%20Analsis.pptx)

  
