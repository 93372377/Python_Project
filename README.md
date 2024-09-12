# Demographic Analysis

## Overall summary:
+ This project offers a comprehensive analysis of key demographic factors across countries, presenting rankings and visual representations through an interactive dashboard. 
+ Users can explore yearly demographic data and geographical distributions. The dashboard includes the following features:

+ 1. Top 10 and Bottom 10 Populated Countries with their respective rankings and geographic locations on a map.
+ 2. Top 10 and Bottom 10 Densely Populated Countries with rankings and map locations.
+ 3. Top 10 and Bottom 10 Migrant Countries with rankings and map highlights
+ 4. Top 10 and Bottom 10 Countries by Median Age, showcasing the oldest and youngest nations, along with map visualizations.
+ 5. Top 10 and Bottom 10 Fertility Rates by country ranking and geographic mapping.
+ 6. Top 10 and Buttom 10 Rich countries based on their GDPs.

+ Finally, unit and performance tests were done for all the functions.

## Methodology: 
+ Demographic data for 234 countries worldwide was scraped from "https://www.worldometers.info/world-population/population-by-country/" for analysis.
+ GDP per country data for 189 countries was fetched from "www.imf.org/external/datamapper/api/v1/NGDP_RPCH?periods=2024" API adress.
+ Two datasets were combined based on the common countries in both data frames.
  
  #### Files:
+ The Python script named Data_Scrapping has been created and utilized for data sourcing.
+ In Main_script each group of countries was mapped and integrated into the interactive dashboard.
+ In Testing script all the functions in both script and main files were tested by unit and performance tests.
+ gdp_data.csv file contains GDP per country data for 189 countries that was fetched from "www.imf.org/external/datamapper/api/v1/NGDP_RPCH?periods=2024" API adress.
+ countries_data.csv file contains Demographic data for 234 countries worldwide that was scraped from "https://www.worldometers.info/world-population/population-by-country/".

## Conclusion
+ By exploring these different categories, users can gain a better understanding of the demographic distribution across different countries worldwide. 
+ This dashboard aims to provide valuable insights and facilitate data-driven decision-making for a wide range of users interested in demographics and global trends.
