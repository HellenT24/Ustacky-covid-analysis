# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

Project Title
Nigeria COVID-19 Data Analysis using Python 

Project Overview
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus, and it has affected major 
parts of the world. Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its 
first case on 27th February 2020.

Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with 
about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its
first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.

In this project, you will employ data science & analytics skills to collect data, explore the data, perform analysis,
create visualizations, and generate insights.

Objectives
-  Understand data collection process, in this case web scraping, and importing from data sources
-  Understand the data cleaning and manipulation process.
- Develop data wrangling skills & data intuition.
- Know how to ask the right questions & find ways to provide answers.
- Develop visualization skills through the use of open-source libraries in Python.
- Generate insights from analysis.
- Report writing 

-Project Steps
Task 1 - Data Collection
Here I obtain the required data for the analysis as described in the project instructions, such as web scrap to obtain data
from the NCDC website, import data from the John Hopkins repository, and import the provided external data.

A - NCDC Website scrap
Website - https://covid19.ncdc.gov.ng/

B - John Hopkins Data Repository
Here you will obtain data from the John Hopkins repository. Your task here involves saving the data from the GitHub repo 
link to DataFrame for further analysis. Find the links below.

Global Daily Confirmed Cases - https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv
Global Daily Recovered Cases - https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv
Global Daily Death Cases - https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv

C - External Data
Save the external data to a DataFrame
External Data includes but not limited to: covid_external.csv, Budget data.csv, RealGDP.csv

Task 2 - View the data
-Use of necessary attributes to obtain the basic information about the data using the head(), info(), shape, .drop() method.

Task 3 - Data Cleaning and Preparation
From the information obtained above, there is a need to fix the data format.

Convert necessary column to appropriate data type.
Rename the columns of the scraped data.
Remove comma(,) in numerical data
Extract daily data for Nigeria from the Global daily cases data

Step 4 - Data Visualization
- Generate a plot that shows the Top 10 states in terms of Confirmed Covid cases by Laboratory test
- Generate a plot that shows the Top 10 states in terms of Discharged Covid cases. Hint - Sort the values
- Plot the top 10 Death cases
- Generate a line plot for the total daily confirmed, recovered and death cases in Nigeria
- Determine the daily infection rate, you can use the Pandas diff method to find the derivate of the total cases.
- Generate a line plot for the above
- Calculate maximum infection rate for a day (Number of new cases) andDetermine the relationship between the external 
dataset and the NCDC COVID-19 dataset. the date
- Generate a barplot using the GDP values for each year & quarters. For example: On x-axis you will have year 2017 and 
the bars will be values of each quarters(Q1-Q4). You expected to have subplots of each quarters on one graph.
- Using axhline, draw a horizontal line through the graph at the value of Q2 2020.
- Generate an insight on the Budget(initial and revised budget) data
- Performed a Time series to visualize the Trend of Covid Ratte in Nigeria.