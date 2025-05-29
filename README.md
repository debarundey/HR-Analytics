# 📊 Employee Attrition Analysis Dashboard

## 🎯 Objective:
The aim of this project is to uncover the key drivers behind employee attrition and offer actionable insights to improve workforce retention. This interactive dashboard serves as a valuable tool for HR professionals to analyze employee turnover trends and make informed decisions.

## Project Highlights:
Throughout this project, I had the opportunity to:

- Explore HR data to extract meaningful insights

- Build dynamic dashboards showcasing critical HR metrics

- Deliver data-driven recommendations for strategic HR planning

## 🔄 Workflow Overview:

- __Data Collection:__

  - Imported the raw .csv dataset into Power BI

  - Loaded the data into Power Query Editor for preprocessing

- __Data Cleaning:__

  - Removed empty columns, duplicates, and errors

  - Renamed columns for clarity and consistency

  - Applied appropriate data types using auto-detection

- __Data Processing:__

  - Created a new column ‘AttritionCount’ using conditional logic:
IF Attrition = 'Yes' THEN 1 ELSE 0

  - Developed Attrition Rate metric using DAX:
Attrition Rate = (SUM(AttritionCount) / SUM(EmployeeCount)) * 100

- __Data Analysis & Visualization:__

  - Designed a variety of visual elements: KPIs, bar charts, pie/donut charts, tables, matrix visualizations, and slicers

  - Applied filters for granular analysis by education field, department, age group, etc.

## 🔍 Key Business Questions Addressed:

- What is the total employee count?

- What are the average age and average salary of employees?

- What is the gender-wise attrition count?

- How many years do employees typically work at the company?

- Which department has the highest number of employees?

- What is the gender distribution across the organization?

- Which education field has the most employees?

- Which type of business travel is most common?

## 📌 Key Features & Learnings:
- __Calculated Fields:__ Used for Attrition Rate and Active Employees

- __Matrix Tables:__ Displayed Job Satisfaction ratings

- __Donut & Pie Charts:__ Illustrated gender and education field distributions

- __Bar & Clustered Charts:__ Compared departments, age groups, and more

- __KPI Cards & Slicers:__ Enabled quick metric tracking and filtering

## 📈 Summary of Insights:

- __Total Employees:__ 1,470 employees currently work at the organization

- __Attrition Count:__ 237 employees left, with higher attrition among males (150 males vs. 87 females)

- __Departmental Attrition:__ Research & Development showed the highest attrition rate (56.13%)

- __Education Field Impact:__ Life Sciences had the highest attrition, requiring targeted retention strategies

- __Job Role Impact:__ Sales roles experienced the highest attrition among job categories

- __Education-wise Attrition:__ Employees with High School education had the highest attrition rate (18.24%)

- __Age Group Trends:__ The age group 25–34 years had the highest attrition count (112 employees)

#
This dashboard enables HR teams to not only track attrition metrics but also take proactive steps to enhance employee satisfaction and retention.

![Preview](https://github.com/debarundey/HR-Analytics/blob/main/dashboard.png)
