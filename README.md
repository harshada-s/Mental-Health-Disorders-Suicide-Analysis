# Global Mental Health Disorders and Suicide Analysis
<p align='justify'> This Tableau dashboard provides insights on how the prevalence of various mental health disorders correlates with suicide rates, both globally and at the individual country level. It uses interactive visualizations to show country and gender specific trends in mental health disorders and suicide rates.

<b>Global and Country-Specific Analysis:</b> Compares suicide and disorder rates across on both global level and within individual countries.
<br><b>Trend Analysis:</b> Identifies trends within disorders and suicide rates over the years from 2000 to 2017.
<br><b>Filters:</b> Allows user to filter on country, disorder and gender for a more in-depth analysis.
<br><b>Key Performance Indicators:</b> Displays average growth rates for disorders and suicide.

link - https://harshada-s.github.io/Mental-Health-Disorders-Suicide-Analysis/
</p>


### Data Source
There are two datasets used in this project, both sourced from Kaggle.
1. [**Global Health Data Analysis 1990-2019**](https://www.kaggle.com/datasets/kamaumunyori/global-health-data-analysis-1990-2019/data)
: This is a collection of mental health disorders datasets from 2000-2019 from various sources the main one being the World Health Organization (WHO).
2. [**Suicide Rate of Countries per Year**](https://www.kaggle.com/datasets/sandragracenelson/suicide-rate-of-countries-per-every-year)
: This dataset lists out countries and their suicide rates from 2000-2017 as published by the World Health Organization (WHO) and other sources.


### SQL 
<p align="justify">
In this project, I connected SQL Server to Tableau. Various SQL queries were used to manipulate and analyze the data. After importing the datafiles, the data was cleaned by filtering out non-relevant rows, removing special characters from strings, renaming columns and using appropriate data types. The suicide rates dataset originally contained individual columns for each year's rates. I applied an unpivot operation to consolidate these into a single 'year' column, resulting in each row representing the suicide rates for each country-year pair. This format aligns with the structure of the mental health dataset. Additionally, I used custom SQL queries in tableau to join various disorder tables. This disorder data was connected to suicide data using tableau relationships.

Check Data folder for the data extract.</p>
