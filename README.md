<img width="629" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/afb1ea64-4d79-40aa-a56d-70dc693d6969">Covid-19 Data Analysis
Table of Contents
Project Overview
Data Sources
Recommendations

Project Overview
This analysis project aims to provide insights into country wise covid-19 related data. By analyzing various aspects of the data,
we seek to identify and compare the impact of the pandemic in various countries and make data-driven precautions.
We aim to find the mortality and recovery rate for various contries, and gain a deeper understanding of the global scenario.

Data Sources
The primary dataset used for this analysis is the "covidData.xlsx" file, containing detailed information about the count of population, confirmed cases, recovered cases, active cases and deaths for each country.

Tools
Excel - Data Cleaning
SQL Server - Data Analysis
PowerBI - Creating reports
Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
Data loading and inspection.
Handling missing values.
Data cleaning and formatting.

Data Analysis

USE covid;
select (SUM(Death)/SUM(Confirmed))*100 AS mortality_rate from coviddata

<img width="629" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/fdb278e4-6567-4d69-952c-a8b2ceb1255e">

