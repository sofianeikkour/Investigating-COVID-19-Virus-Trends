# Investigating-COVID-19-Virus-Trends

### **Context:**
In this project, we will analyze a dataset related to COVID-19 to investigate the virus trends. Luckily, several organizations have shared many datasets allowing the conduction of several kinds of analysis in order to understand this pandemic.

### **Objective:**
The purpose of this project is to identify which countries have had the highest number of positive cases against the number of tests.

### **Dataset:**
The dataset used for this work was collected between the 20th of January and the 1st of June 2020. It contains daily and cumulative number of COVID-19 tests conducted, number of positive, hospitalized, recovered and death cases reported by country. In details here are the columns in the dataset:

1. Date: Date.
2. Continent_Name: Continent names.
3. Two_Letter_Country_Code: Country codes.
4. Country_Region: Country names.
5. Province_State: States/province names; value is All States when state/provincial level data is not available.
6. positive: Cumulative number of positive cases reported.
7. active: Number of active cases on that day.
8. hospitalized: Cumulative number of hospitalized cases reported.
9. hospitalizedCurr: Number of actively hospitalized cases on that day.
10. recovered: Cumulative number of recovered cases reported.
11. death: Cumulative number of deaths reported.
12. total_tested: Cumulative number of tests conducted.
13. daily_tested: Number of tests conducted on the day; if daily data is unavailable, daily tested is averaged across number of days in between.
14. daily_positive: Number of positive cases reported on the day; if daily data is unavailable, daily positive is averaged across number of days in.

**Editor:** This code was written on RStudio.   
**Programming language:** R.   
**Packages:** readr, tibble, dyplr. 
