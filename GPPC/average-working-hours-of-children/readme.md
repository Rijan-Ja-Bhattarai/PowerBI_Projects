# Average weekly working hours of children - Data package

This data package contains the data that powers the chart ["Average weekly working hours of children"](https://ourworldindata.org/grapher/average-working-hours-of-children?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on July 25, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Average working hours of children, study and work, ages 7-14 (hours per week)
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 1999–2016  
Unit: hours per week  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World in Data

#### Full citation
International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World in Data. “Average working hours of children, study and work, ages 7-14 (hours per week)” [dataset]. International Labour Organization, UNICEF, and World Bank, “World Development Indicators” [original data].
Source: International Labour Organization, UNICEF, and World Bank (2025) – processed by Our World In Data

### How is this data described by its producer - International Labour Organization, UNICEF, and World Bank (2025)?
Average working hours of children studying and working refer to the average weekly working hours of those children who are attending school in combination with economic activity.

### Limitations and exceptions:
Although efforts are made to harmonize the definition of employment and the questions on employment in survey questionnaires, significant differences remain in the survey instruments that collect data on children in employment and in the sampling design underlying the surveys. Differences exist not only across different household surveys in the same country but also across the same type of survey carried out in different countries, so estimates of working children are not fully comparable across countries. For detailed source information, see footnotes at each data point.

### Statistical concept and methodology:
Data are from household surveys by the International Labor Organization (ILO), the United Nations Children's Fund (UNICEF), the World Bank, and national statistical offices. The surveys yield data on education, employment, health, expenditure, and consumption indicators related to children's work. Since children's work is captured in the sense of "economic activity," the data refer to children in employment, a broader concept than child labor (see ILO 2009a for details on this distinction).

Household survey data generally include information on work type - for example, whether a child is working for payment in cash or in kind or is involved in unpaid work, working for someone who is not a member of the household, or involved in any type of family work (on the farm or in a business).

### Source

#### International Labour Organization, UNICEF, and World Bank – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://data.worldbank.org/indicator/SL.TLF.0714.SW.TM  


    