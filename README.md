# Top 5 Below Sea Level Countries 

Climate change will disproportionately affect countries at lower sea levels. The objective of this project is to take the top 20 countries identified as being most at risk, look at the GNI, GDP and population trends between the years 2000 - 2050 and to report back the top 5 countries where relief and aid should be directed.


# Data Dictionary

A data dictionary provides a quick overview of features/variables/columns, alongside data types and descriptions. The more descriptive you can be, the more useful this 
document is. This can also be where you describe additional data sources that have been used.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**country**      |*object*|Gapminder - gdp_pcap.csv, gni_per_cap_atlas_method_con2021.csv, Population.csv| the name of the country
|**year**          |*object*|Gapminder - gdp_pcap.csv, gni_per_cap_atlas_method_con2021.csv, Population.csv| the individual year
|**gni_per_capita**|*float* |Gapminder - gni_per_cap_atlas_method_con2021.csv| the gross national income (units in US dollars)
|**population**    |*float* |Gapminder - Population.csv| the total population count by country
|**gdp_per_capita**|*float* |Gapminder - gdp_pcap.csv| the gross domestic product (units in US dollars)

Used following source to get top 20 countries that are considered at risk: https://www.envirotech-online.com/news/environmental-laboratory/7/breaking-news/which-countries-are-most-at-risk-of-rising-sea-levels/35807

# Executive Summary

Climate change will disproportionately affect countries at lower sea levels. The objective of this project is to take the top 20 countries identified as being most at risk, look at the GNI, GDP and population trends between the years 2000 - 2050 and to report back the top 5 countries where relief and aid should be directed.

Data sources that were used in the project were from Gapminder (gdp_pcap.csv, gni_per_cap_atlas_method_con2021.csv, Population.csv), and www.envirotech-online.com for the top 20 countries list that was used to filter down the data. Data cleaning methodology used were filtering by the top 20 countries, looking for NAs in each of the column features, filling the NAs in to complete data, fixing data types, renaming columns, converting string values to floats and merging dataframes into one dataframe to work with. EDA & analysis techiniques used were looking at the summary statistics, getting the standard deviation, and sorting data by different columns. 

Based on the exploration of the data above, we can conclude that the top 5 countries where relief and aid should be directed are Vietnam, Bangladesh, India, Nigeria, and Myanmar. These countries have the lowest GNI per Capita and GDP per Capita, which means they would more open to financial help. In terms of population, India was the only country with the most population. All of the other countries had average populations.

Next steps for this project would be to bring in other aspects that could also be looked at to see if the result would change. Some other data to bring in could be life expectancy, see if there is data about the country relationships to see if the countries that are in need of aid have a good standing relationship (this would determine the likehood of that country being chosen to receive aid). 