# HR-Analytics-in-Tableau
HR Analytics Dashboard in Tableau


## Table of Contents

1. [Introduction](#introduction)
2. [Data Source](#data-source)
3. [Data Preparation and Metrics Calculation](#data-preparation-and-metrics-calculation)
4. [Dashboard Components](#dashboard-components)
5. [Data Analysis](#data-analysis)
6. [Conclusion](#Conclusion)




## Introduction

In today's competitive business environment, retaining talented employees is crucial for organizational success. High attrition rates can lead to increased recruitment costs, loss of productivity, and a decline in employee morale. To address these challenges, HR departments must leverage data to understand the factors driving employee turnover and take proactive steps to improve retention. This project focuses on building an HR analytics dashboard in Tableau to analyze key metrics related to employee attrition, demographic trends, and job satisfaction. The dashboard is designed to provide HR professionals with actionable insights to make data-driven decisions.


## Data Source

- Data Link:

https://www.kaggle.com/datasets/saadharoon27/hr-analytics-dataset



## Data Preparation and Metrics Calculation

# HR Attrition & Workforce Insights Dashboard

This repository contains the Tableau dashboard for analyzing employee attrition and other HR metrics.

## Key Metrics

- **Attrition Rate**: 
  \[
  \text{Attrition Rate} = \frac{\text{SUM([Attrition count])}}{\text{SUM([Employee Count])}}
  \]
  
- **Attrition Count**: 
  \[
  \text{Attrition Count} = \text{IF [Attrition] = 'Yes' THEN 1 ELSE 0 END}
  \]

- **Active Employees**: 
  \[
  \text{Active Employees} = \text{SUM([Employee Count]) - SUM([Attrition count])}
  \]


The dataset used in this project includes employee information such as age, gender, department, job satisfaction, education field, and attrition status. To derive meaningful insights, the following calculated fields were created in Tableau:

**Attrition Rate:** This metric represents the proportion of employees who left the company. It is calculated as:




**Attrition Count:** This field counts the number of employees who left the company. The logic used is:



**Active Employees:** This metric represents the current number of employees still with the company, calculated as:



These metrics were then used to create various visualizations to explore different dimensions of the data.


## Dashboard Components

The dashboard consists of multiple sheets, each focusing on a specific aspect of employee data:

**KPI Sheet:** This sheet displays key performance indicators, including:

- Employee Count
  
- Attrition Rate
  
- Attrition Count
  
- Average Age
  
- Active Employees
  
These KPIs provide a high-level overview of the workforce and its attrition trends.


**Attrition by Gender (Bar Chart):** This sheet visualizes the number of employees who have left the company, segmented by gender. It helps identify if there are gender-specific trends in attrition.

<img width="521" alt="image" src="https://github.com/user-attachments/assets/a82f5322-9e85-418f-b9b8-020d49c10d3e">


**Department with Attrition (Pie Chart):** This pie chart illustrates the distribution of attrition across different departments, allowing HR professionals to pinpoint departments with higher turnover rates.

<img width="338" alt="image" src="https://github.com/user-attachments/assets/ab80eb92-797f-4c30-b070-c93e7f16fc02">


**Number of Employees by Age (Bar Chart):** This chart shows the distribution of employees across different age groups, helping to understand the age demographics of the workforce.

<img width="461" alt="image" src="https://github.com/user-attachments/assets/9853c3c4-9b0d-4779-aca5-571029a67fa9">


**Job Satisfaction with Employee Count (Table):** This table lists the number of employees and their corresponding job satisfaction levels, providing insights into how job satisfaction correlates with employee retention.

<img width="536" alt="image" src="https://github.com/user-attachments/assets/3206b415-0124-4c63-ac28-89a1008c9bfe">


**Education Field Wise Attrition (Bar Chart):** This bar chart analyzes attrition rates based on the education field, helping to determine if certain educational backgrounds are more prone to leaving the company.

<img width="532" alt="image" src="https://github.com/user-attachments/assets/2add7f38-c36b-4f8d-9c07-7b4469f08dd8">


**Attrition Rate by Gender for Different Age Groups (Pie Charts):** This sheet presents five pie charts, each showing the attrition rate for different age groups segmented by gender. It offers a detailed view of how age and gender interact in relation to attrition.

<img width="542" alt="image" src="https://github.com/user-attachments/assets/eaf09b7f-2118-42b4-9281-3241dc1a354e">



## Data Analysis

The analysis reveals several key insights:

**Gender and Attrition:** The "Attrition by Gender" bar chart may show whether one gender is more likely to leave the company, prompting HR to investigate any underlying causes, such as workplace culture or benefits that may disproportionately affect a specific gender.

**Departmental Turnover:** The "Department with Attrition" pie chart highlights departments with higher attrition rates, suggesting that targeted interventions may be needed in those areas to improve employee satisfaction and retention.

**Age Distribution:** The "Number of Employees by Age" bar chart can uncover any potential gaps in age diversity within the company and highlight the age groups most susceptible to attrition.

**Job Satisfaction:** The "Job Satisfaction with Employee Count" table can help correlate job satisfaction with employee retention, showing that lower satisfaction scores might be a precursor to higher attrition rates.

**Educational Background and Attrition:** The "Education Field Wise Attrition" bar chart can reveal if employees from certain educational fields are more likely to leave the company, which could indicate a need for better alignment of job roles with educational backgrounds.

**Age and Gender Analysis:** The "Attrition Rate by Gender for Different Age Groups" pie charts provide a nuanced view of how age and gender impact attrition, helping HR to develop more personalized retention strategies.


## Conclusion

The HR analytics dashboard developed in Tableau offers a comprehensive view of employee attrition and related factors within the organization. By analyzing metrics such as attrition rate, employee demographics, job satisfaction, and department-specific trends, HR professionals can make informed decisions to improve employee retention.

The insights gained from this dashboard can be used to implement targeted interventions, such as enhancing employee engagement programs, offering tailored benefits, or addressing specific issues within departments with high turnover. Additionally, the dashboard serves as a valuable tool for continuous monitoring, enabling the company to proactively address potential attrition risks and maintain a stable, satisfied workforce.

In conclusion, this HR analytics dashboard not only helps in understanding the current state of employee retention but also provides actionable insights to foster a more engaged and committed workforce, ultimately contributing to the long-term success of the organization.







