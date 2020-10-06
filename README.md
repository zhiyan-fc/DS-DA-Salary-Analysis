<h1 align="center"> Job Salary Analysis </h1>  

## Introduction:
- This project aims to help job seekers interested in data scientist and data analyst positions to determine the target location and employers. The data is about the [salary of the data scientist and data analyst H1B sponsored job from January to September of 2020](https://h1bdata.info/index.php?em=&job=data&city=&year=2020).                                  
- This project starts with web scrapping from the original website and subset the data into hiring information about data scientists and data analysts. Three datasets were analyzed in this project: the dataset includes data scientists and data analysts, the dataset of data scientists, and the dataset of data analysts.                 
- To help job applicants identify the employers, locations with most job opportunities, the analysis process includes identifying the relationship among salary, employers, locations, as well as case status. 

## Goal
- Use beautiful soup package scrap raw data from the target website.
- Clean the scrapped data and correct the formats of the variable for further analysis. 
- Identify and remove the outliers.
- Subset cleaned dataset into the dataset of data scientists and dataset of the data analyst.
- Understand the salary distribution of the data related job, data scientist positions, and data analyst positions.
- Identify the most hiring employers, the most hiring states, and most hiring cities.
- Identify the most paying employers, the most paying states, and most paying cities.
- Use bar charts, crosstabs, treemaps, swarm plots to aid the data presentation.


## Outline
- <b>1. Web Crawl</b>    
 - 1.1 Crawb the raw data    
 - 1.2 Keep related data
 - 1.3 Scrape Data
 - 1.4 Correct Format
     - 1.4.1 Salary
     - 1.4.2 Location
     - 1.4.3 Case Status
 - 1.5 Detect and remove outlier
 - 1.6 Subset DS data and DA data
     - 1.6.1 Data Scientist
     - 1.6.2 Data Analyst
     
- <b>2. Overview Analysis</b>    
 - 2.1 Salary Analysis
     - 2.1.1 Salary Distribution
     - 2.1.2 Top 10 Highest Paying Employers
     - 2.1.3 Number of Hiring by Top 10 Highest Paying Employers
     - 2.1.4 Top 10 Highest Paying States
     - 2.1.5 Number of Hiring by Top 10 Highest Paying States
     - 2.1.6 Top 10 Highest Paying Cities
     - 2.1.7 Number of Hiring by Top 10 Highest Paying Cities
     - 2.1.8 Average Salary by Case Status     
     - 2.1.9 Average Salary of Top 10 Highest Paying Employers by Case Status
     - 2.1.10 Average Salary of Top 10 Highest Paying State by Case Status    
     - 2.1.11 Average Salary of Top 10 Highest Paying Cities by Case Status
 - 2.2 Location Analysis
     - 2.2.1 Location of Top 10 Highest Hiring Employers
     - 2.2.2 Location of Top 10 Highest Hiring States
     - 2.2.3 Location of Top 10 Highest Hiring Cities
 - 2.3 Case Status Analysis
     - 2.3.1 Top 10 States by Case Status
     - 2.3.2 Case Status and Base Salary of Top 10 Hiring Employers
     - 2.3.3 Case Status and Base Salary of Top 10 Hiring States
     - 2.3.4 Case Status and Base Salary of Top 10 Hiring Cities
- <b>3. Analysis of Scientist and Data Analyst</b>  
 - 3.1 Salary Distribution
     - 3.1.1 Salary Distribution
     - 3.1.2 Top 10 Highest Paying Employers
     - 3.1.3 Average Salary of Top 10 Highest Paying Employers
     - 3.1.4 Number of Hiring by Top 10 Highest Paying Employers
     - 3.1.5 Top 10 Highest Paying State
     - 3.1.6 Average Salary of Top 10 Highest Paying States
     - 3.1.7 Number of Hiring by Top 10 Highest Paying States
     - 3.1.8 Top 10 Highest Paying Cities
     - 3.1.9 Average Salary of Top 10 Highest Paying Cities     
     - 3.1.10 Number of Hiring by Top 10 Highest Paying Cities
     - 3.1.11 Average Salary by Case Status
     - 3.1.12 Average Salary of Top 10 Highest Paying Employers by Case Status    
     - 3.1.13 Average Salary of Top 10 Highest Paying States by Case Status
     - 3.1.14 Average Salary of Top 10 Highest Paying Cities by Case Status
 - 3.2 Location Analysis     
     - 3.2.1 Location of Top 10 Highest Hiring Employers
     - 3.2.2 Location of Top 10 Highest Hiring States
     - 3.2.3 Location of Top 10 Highest Hiring Cities     
 - 3.3 Case Status Analysis
     - 3.3.1 Top 10 Hiring States by Case Status
     - 3.3.2 Average Salary of Top 10 Hiring States by Case Status
     - 3.3.3 Average Salary of Top 10 Hiring Cities by Case Status     
