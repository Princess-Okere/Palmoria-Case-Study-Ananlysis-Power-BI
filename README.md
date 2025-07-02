# Palmoria-Case-Study-Ananlysis-Power-BI
A Power BI dashboard project analyzing HR data from Palmoria Group, focusing on gender distribution, salary structure, and bonus allocation as part of the DSA data analysis certification.

##  Project Overview
This Power BI project is part of a data analysis course at *Digital Skillup Africa (DSA)*. The task involved examining HR data from Palmoria Group, a manufacturing company in Nigeria, to investigate gender-related concerns, salary structures, and bonus allocation using interactive Power BI visuals.

##  Data Cleaning
Before analysis, the following data preparation steps were taken:
- Replaced missing or undisclosed genders with a generic status ("Undisclosed").
- Removed rows with "NULL" departments.
- Removed records with missing salary values.
- Merged the Bonus Rules data with the employee data by transforming it through unpivoting and calculated columns.
- Created calculated columns/measures for:
  - Bonus Amount
  - Total Pay
  - No Bonus tag
  - Salary Band (Grouped by $10,000 intervals)

##  Key Analysis and Visualizations
### 1. Gender Distribution by Region and Department
- *Chart Type*: Clustered Column Chart
- *Insight*: Near gender parity across most departments and regions. Minor gaps observed in Legal and Product Management departments.

### 2. Rating Distribution by Gender
- *Chart Type*: Clustered Bar Chart
- *Insight*: All genders had relatively balanced average ratings. However, some 'Undisclosed' categories showed slightly higher average salaries.

### 3. Gender Pay Gap by Region and Department
- *Chart Type*: Clustered Column Charts
- *Insight*: Slight differences in salary averages per gender were observed in regions like Lagos and Abuja. Undisclosed genders had higher averages in some departments.

### 4. Compliance with Minimum Salary Regulation
- *Requirement*: Minimum salary must be $90,000
- *Measure Created*: Meets Minimum Salary
- *Chart Type*: Card and Column Chart
- *Insight*: Majority of employees fall below the regulatory threshold, especially in certain departments.

### 5. Salary Band Distribution
- *Chart Type*: Column Chart with Salary Band on Axis
- *Insight*: Most employees earn between $70,000 and $90,000. Few exceed $110,000.
- *Slicer*: Region-based slicer included.

### 6. Bonus Allocation & Total Pay
- *Measure*: Bonus Amount based on performance rating.
- *Total Pay* = Salary + Bonus
- *Visuals Used*:
  - Bar Chart (Total Pay by Region)
  - Card Visual (Total Pay company-wide)

##  Tools Used
- Microsoft Power BI
- DAX for calculated columns/measures
  
##  Conclusion
This project was an in-depth analysis of the HR data for Palmoria Group, a manufacturing company grappling with gender inequality concerns. The Power BI dashboard built from this analysis provided clear, data-driven insights into workforce demographics, salary structure, and bonus distribution.
Through careful data cleaning, transformation, and visualization, the project highlighted several issues—such as potential gender pay gaps in some departments and regions, salary disparities, and unequal rating distributions. These insights offer management a strategic overview of where to focus policy changes and interventions.
Ultimately, the dashboard serves as a practical decision-making tool, enabling stakeholders to monitor workforce equity and take proactive steps to foster inclusivity and compliance with labor standards.

##  Key Lessons Learnt:
Throughout the course of this project, the following key lessons and skills were developed:

Data Cleaning in Power BI: Learned to remove null values, filter incomplete records, and manage missing gender entries using Power Query.

Data Modeling & Relationships: Understood how to structure multiple datasets (Employee Data and Bonus Rules), define relationships, and troubleshoot merge conflicts.

Calculated Columns & Measures: Gained proficiency in writing DAX formulas to derive bonus amounts, total pay, salary bands, and other custom insights.

Data Visualization: Developed various types of insightful visuals—bar charts, pie charts, cards, and clustered columns—to communicate findings effectively.

Insightful Storytelling with Data: Practiced interpreting complex data by breaking it into meaningful stories around gender equality, compensation fairness, and regulatory compliance.

Real-World HR Analytics: Applied analytics in a real business context, simulating how companies use data to identify and fix systemic inequalities.

GitHub Portfolio Building: Strengthened portfolio presentation skills by creating a clear, documented repository showcasing analysis workflow, visual outputs, and business recommendations.

