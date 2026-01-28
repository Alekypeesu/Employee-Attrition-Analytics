# **Employee Attrition Analytics** 📊
### *Data Analysis & Reporting Project*

---

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=flat&logo=rstudio&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-0B3C5D?style=flat&logo=markdown&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

---

## **HTML Report Preview**

The rendered HTML report generated from the RMarkdown analysis.  
![HTML Report Preview](https://github.com/Alekypeesu/Employee-Attrition-Analytics/blob/main/preview.png)

---

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Project Overview**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

This project analyzes **employee attrition patterns** using a real-world human resources dataset.  
The objective is to identify key factors that contribute to employee turnover and generate insights that support **data-driven HR decision-making**.

The analysis combines **data preparation**, **exploratory data analysis**, and **visual reporting**, with results documented in an RMarkdown file and presented through a rendered HTML report.

### **Key Objectives**
- Identify primary drivers of employee attrition  
- Analyze attrition patterns across departments and job roles  
- Evaluate the impact of compensation, satisfaction, and tenure  
- Produce a reproducible and well-documented analysis workflow  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Dataset Description**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The analysis is based on the **IBM HR Employee Attrition dataset**, which contains structured employee-level data related to demographics, job roles, compensation, performance, and workplace satisfaction.

### **Dataset Features**
- Employee demographics (age, gender, marital status, education)
- Job-related factors (department, role, job level, overtime)
- Compensation details (monthly income, salary bands, stock options)
- Workplace indicators (job satisfaction, work-life balance, environment satisfaction)
- Performance metrics (performance rating, years at company)
- Attrition status (Yes / No)

### **Dataset Summary**
- Records: 1,470 employee observations  
- Features: 35 variables (categorical and numerical)  
- Attrition rate: Approximately 16%  
- Missing values: None  

**Dataset file used**
- WA_Fn-UseC_-HR-Employee-Attrition.csv

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Methodology**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The analysis followed a structured, CRISP-DM-inspired workflow:

### **1. Data Preparation**
- Imported and inspected dataset structure
- Checked for missing values and inconsistencies
- Converted categorical variables for analysis
- Created derived features such as tenure groups and income categories

### **2. Exploratory Data Analysis (EDA)**
- Analyzed attrition trends across departments and job roles
- Compared income levels, tenure, and satisfaction scores
- Examined demographic patterns associated with attrition
- Investigated correlations among key variables

### **3. Statistical Analysis**
- Performed descriptive statistics
- Applied hypothesis testing (t-tests and chi-square tests)
- Examined feature importance related to attrition risk

### **4. Visualization & Reporting**
- Developed clear visual summaries using ggplot2
- Created tables highlighting key trends and comparisons
- Compiled insights into a structured, readable report
- Automated reporting using RMarkdown

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Tools & Technologies**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The project was developed using the following tools:

- R
- RStudio
- RMarkdown
- Tidyverse (dplyr, ggplot2)
- knitr for dynamic report generation

The complete analysis workflow is documented in the RMarkdown file, with the final results presented in an HTML report.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Project Structure**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

```text
Employee-Attrition-Analytics/
├── Data.DA5030.Project.Rmd
├── Data.DA5030.Project.html
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
└── README.md
```

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **File Descriptions**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Data.DA5030.Project.Rmd  
  Contains the full analysis code, explanations, and visualizations, including data preparation, EDA, statistical analysis, and plotting.

- Data.DA5030.Project.html  
  Rendered version of the report for direct viewing in any web browser.

- WA_Fn-UseC_-HR-Employee-Attrition.csv  
  Source dataset containing employee records and attrition status.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Key Insights**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

The analysis indicates that employee attrition is influenced by a combination of **job satisfaction**, **income level**, **tenure**, and **departmental role**.

Key findings include:
- Higher attrition rates among early-career employees (1–3 years tenure)
- Increased turnover in specific job roles and departments
- Strong relationship between low satisfaction scores and attrition
- Overtime and compensation levels playing a significant role in attrition risk

These findings highlight areas where targeted retention strategies may be most effective.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **How to View the Report**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- Open Data.DA5030.Project.html in any web browser  
- Or open Data.DA5030.Project.Rmd in RStudio and knit the report to reproduce the analysis

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **Author**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Alekypeesu  
Data Analytics Project

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## **License & Usage**
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

This project is intended for **educational and analytical purposes** only.  
The dataset is publicly available and used here for analysis and demonstration purposes.
