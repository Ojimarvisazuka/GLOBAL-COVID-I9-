# GLOBAL-COVID-I9

![](Covid_Virus.jpg)

## Introduction
This project was mandated by Quantum Analytics NG as part of my internship. The instruction was to carry out a live analysis of COVID-19 dataset from the World Health Organisation (WHO) website for an update on COVID-19 events. Power BI was the visualization tool used and the details are presented below. 


## Problem Statement
The idea behind this project was to get an up-to-date rundown of active and live events regarding Covid-19. Others include:

- Find out what the trend has been like overtime
- Know the worst hit Nations 
- Know which time of the year records the highest virus spread
- Develop a containment model or plan to cope with the virus going forward.


## Data Sourcing
To access the data needed for this project,  I visited the WHO website which you can find [here](https://covid19.who.int/).
I imported the web link to the Power BI desktop web-link page; selected the relevant tables to the project and loaded it to the Power Query Editor for transformation and cleaning in order to ensure data quality. The dataset is a combination of two tables.  Table-1 has 8-columns and 237-rows while the second table contains 11 columns and 305,019 rows.


## Data Transformation/Cleaning
The following steps were taken to ensure quality:

- Column Profiling based on entire dataset
- Removed duplicates
- Replaced empty (null) cells for cases and death records with zero (0)
- Created new columns from the  "Date reported" column. These columns are the "Year", "Month" and "Numerical Month". To achieve this, I duplicated the original column and "transformed" it accordingly for each column.
- Checked and ensured data types were matching and corresponding

## Data Modelling
Having Tansformed and claeaned the data, I proceeded to close and apply the changes on Power BI. Although there were 2 tables. However, only one major relationship was spotted between the tables, which is the "country". A view of the model can be seen below:


![](Covid-19_Model.png)


## Visualization
After the necessary transformation/cleaning and Modelling, the data was considered fit for visualization and insights were generated using key KPI metrics. Below is the single page dashboard generated for this project:

![](Global_covid-19_dashboard_page.jpg)

For the interactive visual, see [here](https://app.powerbi.com/groups/me/reports/84beac97-845d-4d25-9c31-bc198d474b9c?experience=power-bi)




## Conclusion 
The project was able to identify the trend of cases, and it was observed that peak figures were recorded in the 1st Quarter of 2022 with the US, Brazil and India recording the top 3 total cases globally (hitherto). Although, the World Health Organisation (WHO) no longer considers the virus a Public Health Emergency of International Concern (PHEIC). However, the trend of event shows that cases were reported within the last 7 days; indicating that the virus is around and endemic. 


## Recommendation
Despite relaxing stringent Covid-19 measures, various Governments are advised to put in place various containment and coping measures in the event of a future upsurge in covid-19 cases. People are also advised to adhere to the covid-19 guidelines especially during cold-winter months, since more cases are usually recorded during that period of the year.

