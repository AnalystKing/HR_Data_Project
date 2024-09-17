## HR Data Analysis And Dashboard
### Project Overview
This data analysis project using a HR dataset aims to provide insight into attrition trends, job performance and satifaction levels as well as employee self development rate. It also seeks to analyze the gender, marital and age balance of employees in the organzation. 

### Data Sources
HR Data: The primary dataset used for this analysis is the 'HR_Data.csv' file containing important information about each employee in the organization. The dataset is sourced from [here](https://docs.google.com/spreadsheets/d/17zaiJnUOnLdHROWLZYcVlpMJ08wh-Bou/edit?gid=115883679#gid=115883679)

### Tools
The primary tool used in this analysis is Excel [(Download here)](https://microsoft-excel.en.softonic.com/download). Excel was used for the following processes:
- Extracting the data
- Cleaning and exploring the data
- Analyzing the data
- Visualizing the data and creating a dashboard.

### Data Cleaning/Preparation
In the initial data preparation stage, we performed the following tasks;
- Data loading and inspection
- Checking formatting and handling missing values
- Data cleaning and formatting

### Exploratory Data Analysis (EDA)
EDA involved exploring the employee data to answer key questions, such as;
- What is the number of employees and attrition rate in the organization?
- What is the performance and satisfaction level of employees in the organization?
- What is the age and gender balance of employees across each department?
- How often did employees strive to improve their selves through training in the previous year?

### Data  Analysis
Some of the functions or syntax used during analysis in excel includes: 
- Current number of employees
```excel
=SUM(CF.current Employee column)
```

- Attrition rate
```excel
=(GETPIVOTDATA("Employee Count",$C$2)-GETPIVOTDATA("CF_current Employee",$A$2))/GETPIVOTDATA("Employee Count",$C$2)
```

- Average Age
 ```excel
  =AVERAGE(Age_column)
```

### Results/Findings
Some of the analysis results are as follows:
- There are currently **1,233** employees in the organization with the overall attrition rate of **16%**. About 237 employees have left the organization within the time scope of the dataset.
- The average performance rating of employees in the organization is **3** out of **5**. While the job and environment satiscation levels can be considered satisfactory or very good as majority of the employees rate it a **3** or **4** out of **4**.
- 
