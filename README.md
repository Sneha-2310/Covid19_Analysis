Covid-19 Data Analysis
<br>
Table of Contents<br>
Project Overview<br>
Data Sources<br>
Recommendations<br>

Project Overview
This analysis project aims to provide insights into country wise covid-19 related data. By analyzing various aspects of the data,<br>
we seek to identify and compare the impact of the pandemic in various countries and make data-driven precautions.<br>
We aim to find the mortality and recovery rate for various contries, and gain a deeper understanding of the global scenario.<br>
<br>
Data Sources
The primary dataset used for this analysis is the "covidData.xlsx" file, containing detailed information about the count of population, <br>
confirmed cases, recovered cases, active cases and deaths for each country.
<br>
Tools<br>
Excel - Data Cleaning<br>
SQL Server - Data Analysis<br>
PowerBI - Creating reports<br>
Data Cleaning/Preparation<br>
<br>
In the initial data preparation phase, we performed the following tasks:<br>
Data loading and inspection.<br>
Handling missing values.<br>
Data cleaning and formatting.<br>
<br><br>
Data Analysis<br>
SQL CODE: <br>
<br>
USE covid;<br>
select (SUM(Death)/SUM(Confirmed))*100 AS mortality_rate from coviddata
<br><br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/fdb278e4-6567-4d69-952c-a8b2ceb1255e">
<br>
This gives us the global average  mortality rate
<br>
USE covid;<br>
select (SUM(Recovered)/SUM(Confirmed))*100 AS mortality_rate from coviddata
<br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/9ba21bf9-8ecf-4a26-aee5-cef1f29d51ce">
<br>
This gives us the global average recovery rate
<br><br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/dd2ed37d-fa42-43cc-ad16-8a27e657bc9c">
<br><br>
The data aligns with the one calculated in the PowerBI Dashboard.
<br><br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/97f7ff0b-10ec-4eb8-9ec7-40be2652e3b5">
<br><br>
 Next, we made a dashboard of this data as shown below
<br>
<img width="555" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/08d29399-814a-45b4-a04e-6d8dda949a96">
<br><br>
The dashboard provides us a dynamic insight to the data of each country seprately. We have alsoadded a search visual for that purpose.
<br><br>
<img width="555" alt="image" src="https://github.com/Sneha-2310/Covid19_Analysis/assets/98509803/2a80ecfa-0c00-46be-b04f-43b12719a8e4">
<br><br>
Recommendations:<br>
We can conclude that United state has been most affected by the pandemic. The mortality and contengency rate could be compared using the dashboard <br>
and preventive measures should thus be taken accordingly. <br>



