# Employee Attrition Rate ( HR Data Analysis using Power BI)
Analysis of HR data using the PowerBI tool

### Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [References](#references)

---

### Project Overview
---

This data analysis project aims to provide insight into the professional HR Data analysis of a company. By analyzing various aspects of the HR data, I seek to identify the trends and gain a deeper understanding of new hires and existing employee retention.

### Problem Statement

"Market fluctuations and rapidly changing technology have affected the global market. Many published reports showed that around half of the employees wanted to change jobs. While some market researchers said that flexible working and job security were their primary factors, few admitted that a higher salary was their aim.

Different regions saw an increase and a decrease in salaries over the years. While the increase was to retain top-level professional employees, the pay cuts were due to market fluctuations and were reported after the market conditions improved. HR people across the globe are hiring new employees, trying to retain and understand the needs of employees who got separated (those who left the company).

So, how does the HR department make these decisions in volatile market conditions? They rely on HR analytics to understand the existing situation and develop a new modern approach. For this requirement, you have been asked in your company to build a dashboard in Power BI considering the challenges of HR people and provide an effective way to find the answers to their day-to-day questions."

Task- Use the HR data set provided for this project and analyze that to understand the data and terms and provide insights.

### Data Sources 

HR Data: The primary dataset used for this analysis is the "HR-Data.xlsx" file,
containing employee information.
This project was a capstone project, part of the Coursera PowerBI advanced skill development course.  The data is taken from Coursera. 

### Tools 
Tools used for Data Cleaning, Data Analysis and Report generation :
- Excel
  [Download here]
- PowerBI

### Data Cleaning

In the initial data preparation phase, I performed the following tasks:
- Data loading and inspection,
- Changing data types,
- Optimizing the dataset by removing unnecessary and duplicate columns,
- Standardizing abbreviations used in the dataset,
- Handling missing values,
- Data cleaning and formatting,
- Managing Relationships between different tables.

### Exploratory Data Analysis

EDA involved exploring the HR data to answer key questions, such as:

- What are the recruitment trends?
- What are New Hires, Retention and Separation trends?
- What are Male, and Female staff with age groups that have been retained over the years in every region?

### Data Analysis

Include some interesting codes/features that I have worked with
- DAX functions, Calculated columns and Measures. For example
  ~~~ DAX function
      EmpCount =
      CALCULATE (
      COUNT ( Employee[EmplID] ),
        FILTER (
          ALL ( 'Date'[PeriodNumber] ),
          'Date'[PeriodNumber] = MAX ( 'Date'[PeriodNumber] )
          )
          )
  ~~~

- Advanced visualization charts like Horizontal Funnel, Tornado, Ribbon and Aster plot charts etc.
- Customized dashboard.
  
![HR Analysis](https://github.com/SmitaPinjan/HR-Analysis-Dashboard-using-Power-BI/assets/152721562/8f430284-6cb6-4059-8e24-8d7a1a54c3fe)

### Insights

The Analysis results are summarized as follows:
- The company has over 13k employees, Male staff is around 57% and Female staff is 43%.
- Over the past few years, from 2011 till 2014, 11.76K employees have left jobs and noticeably Male staff is higher % as compared to Female staff members.
- The New Hires trend is upward every year with 17.18K new hires from 2011 till 2014.
- Age group of 30 and less are more compared to 30+ employees. Noticeably, new hires under the age of 30 are working as part-time jobs and in West and North regions.
- Employee retention is less in the West and North regions considering these regions have higher recruitment compared to all other regions.

### Recommendations

Based on the analysis, I recommend the following actions:
- The company must focus on West and North regions for employee retention. Management can look into deploying some new measures, programs, perks or benefits for existing employees to ensure they will not leave the company.
- Implement a strategy to retain talented employees who will be an asset to a company.

### References

- Coursera
- Microsoft guide for Power BI

|Heading1|Heading2|
|--------|--------|
|Content |Content2|
|Data Analysis| PowerBI|


