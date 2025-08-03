# Palmora-Group-HR-Analysis

### Table of Content
-    [Project Preview](#Project-preview)
-    [Data Sources](#Data-sources)
-    [Tools Used](#Tools-Used)
-    [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
-    [Exploratory Data Analysis](#Exploratory-data-analysis)
-    [Data Analysis](#Data-analysis)

### Project Overview
---
Based on the case scenario, I will outline a structured approach to analyze the Palmoria Group's HR data, focusing on gender-related issues, and address the specific requirements and questions posed. I will also provide a visualization, and calculations for the bonus payments.

### Data Sources
---
The primary source of data used contains information from Palmora Group.

### Tools Used
---
-  Power BI [Download Here]([https://www.microsoft.com](https://www.microsoft.com/en-us/download/details.aspx?id=58494))
    1. For Data Cleaning and preparation
    2. For Analysis
    3. For Visualization using Charts in Power BI environment
  
### Data Cleaning and Preparation
---
In the initial phase of Data Cleaning and Preparation, we perform the following actions
-    Data Loading and Inspection
-    Data Cleaning and Formatting (Duplicates removed, categories standardized)
-    Included additional columns needed for more analysis.
-    Columns for employees who did not indicate their gender was assigned as "Anonymous"
-    Employees without Salary structure was taken out.
-    Departments with "NULL" was taken out as well.

### Exploratory Data Analysis
---
Below is a summary of the analysis for the tasks given. Each task’s methodology and output are condensed for clarity, with their individual charts;
 
 1. Gender Distribution in the Organization
     - Objective: Determine the gender distribution overall, by region, and by department.
     - Overall Gender Distribution By Region:
        ![1](https://github.com/user-attachments/assets/2f0b569a-1bb5-4eaa-82fb-8125f9093469)

     - Overall Gender Distribution By Department:
        ![4](https://github.com/user-attachments/assets/b263a373-d8e2-4df8-a7b2-60809ca332cb)


Insight: From the chart above it is clearly indicated that departments such as Product Management, Legal and Accounting are heavily male-dominated, this could indicate occupational segregation, contributing to gender inequality perceptions. I would Suggest that Management should focus on diversifying hiring in these departments.

 2. Insights on Ratings Based on Gender
    - Objective: Analyze performance ratings by gender to identify potential biases

    - Distribution of Performance Ratings by Gender
    ![7](https://github.com/user-attachments/assets/837541ed-1618-4aa8-b5d2-6d151beba0be)


    - Distribution of Performance Ratings of Gender By Department
    <img width="1234" height="697" alt="9" src="https://github.com/user-attachments/assets/10e99710-2be4-4e2e-ae48-560030b8ec24" />

Insight: From the chart above, Males receive higher ratings in departments such as Legal, Product Managemnt and Support. This may suggest bias in performance evaluations, especially in male-dominated areas. Managemnt should review rating criteria and ensure standardized, objective evaluation processes.

3. Salary Structure and Gender Pay Gap
    - Objective: Analyze the salary structure to identify the gender pay gap and pinpoint departments and regions for management
    -  Gender Pay Gap by Department

    ![3](https://github.com/user-attachments/assets/15e0062b-25cd-41de-9efa-857c4a3d169c)

Key findings: Departments with Larger Pay Gaps such as Business Development and Engineering should be prioritized for Salary audits and adjustments.
Insights: The Gender pay gap exists particularly in male-dominated departments. Management should conduct a detailed pay equity analysis, focusing on the male-dominated departments and consider factors like job roles, experience and hours worked to address disperities.


4. Minimum Salary Regulation($90,000)   -

   - Objective: Assess compliance with the $90,000 minimum salary regulation and analyze Salary distribution
   - Salary Bands by Region and Gender
### Data Analysis
---
This is where we include some basic llines of codes or Queries or even some of the DAX expressions used during your analysis;

```  SQL
Select * From A, B, C
Where A> 15
```
### Results/Findings


### Recommendations
