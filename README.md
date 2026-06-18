
# HR Data Analysis Project

## Project Overview

This project focuses on analyzing employee attrition and retention patterns using HR analytics data. The dashboard provides insights into workforce trends, employee turnover, job roles, departments, income groups, age demographics, and tenure-related factors that influence attrition.

The analysis is based on a dataset containing employee information such as department, job role, gender, age, education field, monthly income, years at the company, years since last promotion, and attrition status. Interactive visualizations help identify key drivers of employee turnover and support data-driven HR decision-making to improve employee retention and organizational performance.

 ## Objectives

- To analyze the overall workforce and attrition performance using key HR metrics such as total employees, attrition count, attrition rate, average hourly rate, and average years at the company.
- To evaluate attrition trends across different departments and identify areas with higher employee turnover.
- To analyze attrition rates by job role and determine which positions are most affected by employee departures.
- To study the relationship between years at the company and attrition rate to understand employee retention patterns over time.
- To examine the impact of years since last promotion on employee attrition and identify potential career-growth concerns.
- To analyze attrition across different age groups and identify demographic segments with higher turnover rates.
- To evaluate attrition patterns across education fields and understand how educational backgrounds influence employee retention.
- To assess the relationship between monthly income levels and attrition rates to determine whether compensation affects employee turnover.
- To analyze work-life balance ratings across job roles and explore their influence on employee retention.
- To compare average working years across departments and identify differences in employee tenure.
- To provide interactive filtering by department, job role, and gender, enabling users to explore attrition trends dynamically and support data-driven HR decision-making.


 ## Dataset Information

* **Source**: HR Dataset
* **Total Records**: 50,000+
* **Key Columns**:

**HR_1** :
   * Age	
   * Attrition	
   * BusinessTravel	
   * DailyRate	
   * Department	
   * DistanceFromHome	
   * Education	
   * EducationField	
   * EmployeeCount	
   * EmployeeNumber	
   * EnvironmentSatisfaction	
   * Gender	
   * HourlyRate	
   * JobInvolvement	
   * JobLevel	
   * JobRole	
   * JobSatisfaction	
   * MaritalStatus

**HR_2** :
   * Employee ID	
   * MonthlyIncome	
   * MonthlyRate	
   * NumCompaniesWorked	
   * Over18	
   * OverTime	
   * PercentSalaryHike	
   * PerformanceRating	
   * RelationshipSatisfaction	
   * StandardHours	
   * StockOptionLevel	
   * TotalWorkingYears	
   * TrainingTimesLastYear	
   * WorkLifeBalance	
   * YearsAtCompany	
   * YearsInCurrentRole	
   * YearsSinceLastPromotion	
   * YearsWithCurrManager


			
## Data Cleaning & Preparation

To ensure accurate and reliable analysis, the HR datasets (HR_1 and HR_2) were cleaned, validated, and transformed before building the dashboard.

**Data Cleaning**

Checked for and removed duplicate employee records to maintain data consistency.
Verified data types and ensured numerical fields were stored in the correct format.
Handled missing or null values using appropriate data-cleaning techniques.
Removed blank entries and corrected inconsistent categorical values.
Standardized column names for easier data modeling and analysis.
Validated Employee ID/Employee Number fields to establish accurate relationships between HR_1 and HR_2 datasets.

**Data Preparation**

Merged HR_1 and HR_2 datasets using Employee ID to create a unified employee dataset.
Created calculated measures for:
Total Employees
Attrition Count
Attrition Rate
Average Hourly Rate
Average Monthly Income
Average Years at Company
Grouped employees into Age Groups for demographic analysis.
Created Income Brackets to analyze attrition across salary ranges.
Derived tenure-based metrics using YearsAtCompany, YearsInCurrentRole, and YearsSinceLastPromotion.
Categorized employees by Department, Job Role, Gender, and Education Field for comparative analysis.
Prepared the data model to support interactive filtering and dashboard visualizations.

## Tools & Technologies Used

* Microsoft Excel
* Power BI
* Tableau




## Data Modeling

* Connected multiple tables using relationships
* Created a data model for better analysis




## Key KPIs (Key Performance Indicators)

The following KPIs were used to evaluate employee attrition, workforce demographics, and retention trends within the organization.

### Overall KPIs

* **Total Employees:** 50,000
* **Attrition Count:** 25,000
* **Attrition Rate:** 50.21%
* **Average Hourly Rate:** 115.4
* **Average Years at Company (Tenure):** 10.77 Years
* **Average Monthly Income:** Calculated from employee salary records

### Analytical KPIs

#### Attrition Rate by Department

* Measures employee turnover across departments.
* Helps identify departments experiencing higher attrition and potential retention challenges.

#### Attrition Rate by Job Role

* Compares attrition rates among different job roles.
* Identifies positions with the highest employee turnover.

#### Attrition by Age Group

* Analyzes employee departures across different age demographics.
* Highlights workforce segments with higher attrition counts.

#### Attrition by Education Field

* Evaluates attrition patterns across educational backgrounds.
* Helps understand whether specific education fields are associated with higher turnover.

#### Attrition by Monthly Income

* Examines the relationship between salary levels and employee attrition.
* Compares attrition rates across low-, mid-, and high-income groups.

#### Attrition vs Years at Company

* Analyzes employee retention based on tenure.
* Identifies critical periods when employees are more likely to leave the organization.

#### Attrition vs Years Since Last Promotion

* Evaluates the impact of career progression on employee retention.
* Helps identify whether delayed promotions contribute to employee turnover.

#### Work-Life Balance Analysis

* Measures work-life balance scores across job roles.
* Assesses the potential influence of work-life balance on employee satisfaction and retention.

#### Department-wise Average Working Years

* Compares average employee tenure across departments.
* Provides insights into long-term workforce stability and retention.

#### Demographic Analysis

* Evaluates attrition trends by gender, age group, and other employee demographics.
* Supports diversity and workforce planning initiatives.

### Dashboard Features

* Interactive filtering by **Department**, **Job Role**, and **Gender**.
* Dynamic visualizations for attrition, retention, compensation, and workforce demographics.
* Drill-down capabilities to identify key drivers of employee turnover.
* KPI cards and charts designed to support data-driven HR decision-making and retention strategies.



## Challenges Faced

* Handling large dataset
* Cleaning inconsistent data
* Managing multiple file connections



## Learnings

* Improved data cleaning skills
* Learned data modeling concepts
* Gained hands-on experience in dashboard creation
* Developed analytical thinking



## Conclusion

This project provides meaningful insights and helps understand what makes a project successful.



## Author

**Mrunali Sapkal**

* 📧 Email: mrunalisapkal34@gmail.com
* 🔗 LinkedIn: www.linkedin.com/in/mrunali-sapkal-a8b4211b2
