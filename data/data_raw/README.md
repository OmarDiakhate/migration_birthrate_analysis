This directory contains all raw data that is external to the project.

README:

Project Title - 
Exploring the Correlation Between Net Migration Rates and Birth Rates Overtime:
A Cross-National Study

Research Question - 
How do changes in net migration rates correlate with subsequent changes in total
fertility rates (TFR) within host countries over time, and what socioeconomic
factors might mediate this relationship?

Data Source - 
Link: https://databank.worldbank.org/source/world-development-indicators#
The data used for this project was sourced from the World Bank's World 
Development Indicators (WDI). The WDI provides complete cross-national
statistics on a range of development categories, compiled from
officially-recognized international sources.

File Overview -
File: world_bank_data.csv
This csv file contains data from 217 countries with the following structure:
  Country Name: Full name of the country
  Country Code: ISO 3-letter country code
  Series Name:
    Net migration: the net number of migrants (inflow - outflow) per year
    Total Fertility Rate (TFR): average number of children born per woman over
    her lifetime
    GDP per Capita (constant 2015 US$): Real Gross Domestic Product adjusted for
    inflation
    Urban Population (% of Total): percentage of the population living in urban
    areas
    Employment to Population Ratio, 15+, Female (%) (modeled ILO estimate):
    the proportion of the female working-age population that is employed
  Series Code: World Bank code for the indicator
  1960 [YR1960] to 2024 [YR2024]: Annual data from each year (1960 to 2024)

Each country appears five times in the data set, once for each series category)