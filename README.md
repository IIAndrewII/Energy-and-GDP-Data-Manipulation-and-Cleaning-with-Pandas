# Energy and GDP - Data Manipulation and Cleaning with Pandas

## In this notebook we will use:
- The energy data from the file `Energy Indicators.xls`, which is a list of indicators of [energy supply and renewable electricity production](Energy%20Indicators.xls) from the [United Nations](http://unstats.un.org/unsd/environment/excel_file_tables/2013/Energy%20Indicators.xls) for the year 2013.
- The GDP data from the file `world_bank.csv`, which is a csv containing countries' GDP from 1960 to 2015 from [World Bank](http://data.worldbank.org/indicator/NY.GDP.MKTP.CD).
- The [Sciamgo Journal and Country Rank data for Energy Engineering and Power Technology](http://www.scimagojr.com/countryrank.php?category=2102) from the file `scimagojr-3.xlsx`, which ranks countries based on their journal contributions in the aforementioned area.

#### To answer import questions in the context of only the top 15 countries by Scimagojr Rank over the last 10 years for each country as:
- What is the `average GDP` for each country? 
- What is the mean of `Energy Supply per Capita`?
- What country has the maximum `% Renewable` and what is the percentage?
- What is the ratio of `Self-Citations to Total Citations` for each country? and what country has the highest ratio?
- Which countries has `% Renewable`at or above the median for all countries in the top 15 countries?

#### And to know more about the population in each Continent

### Steps:
1- Load, Validate and Clean the data.

2- Join the three datasets.

3- Answering questions in the context of only the top 15 countries by Scimagojr Rank over the last 10 years for each country.

4- Group the Countries by Continent, then create a dateframe that displays population summary statistics.
