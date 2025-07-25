# Global Hunger Index - Data package

This data package contains the data that powers the chart ["Global Hunger Index"](https://ourworldindata.org/grapher/global-hunger-index?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Global Hunger Index
The Global Hunger Index (GHI) is a tool designed to comprehensively measure and track hunger globally, regionally, and by country. To reflect the multidimensional nature of hunger, the GHI combines four component indicators into one index score. An increase in a country's GHI score indicates that the hunger situation is worsening, while a decrease in the score indicates an improvement in the hunger situation.


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Concern Worldwide and Welthungerhilfe – processed by Our World in Data

#### Full citation
Concern Worldwide and Welthungerhilfe – processed by Our World in Data. “Global Hunger Index” [dataset]. Concern Worldwide and Welthungerhilfe [original data].
Source: Concern Worldwide and Welthungerhilfe – processed by Our World In Data

### Additional information about this data
The Global Hunger Index (GHI) is a tool designed to comprehensively measure and track hunger globally, regionally, and by country. To reflect the multidimensional nature of hunger, the GHI combines four component indicators into one index score. An increase in a country's GHI score indicates that the hunger situation is worsening, while a decrease in the score indicates an improvement in the hunger situation.

The four indicators used to calculate the GHI are:

- Undernourishment: the proportion of undernourished people as a percentage of the population;

- Child wasting: the proportion of children under the age of five who suffer from wasting (low weight for their height, reflecting acute undernutrition);

- Child stunting: the proportion of children under the age of five who suffer from stunting (low height for their age, reflecting chronic undernutrition); and

- Child mortality: the mortality rate of children under the age of five (partially reflecting the fatal synergy of inadequate nutrition and unhealthy environments).

The formula and weighting of these four indicators in relation to the final index score can be found at: https://www.globalhungerindex.org/pdf/en/2021.pdf

The 2021 GHI has been calculated for 135 countries for which data on the four component indicators are available and where measuring hunger is considered most relevant. GHI scores are not calculated for some higher-income countries where the prevalence of hunger is very low.

Where original source data were unavailable, the GHI was estimated based on the most recent data available. For 19 countries, individual scores could not be calculated owing to lack of data. 12 of those countries (Burundi, Comoros, Guinea, Guinea-Bissau, Moldova, Niger, South Sudan, Syria, Tajikistan, Uganda, Zambia, and Zimbabwe) were provisionally designated by severity. In OWID's dataset, the GHI of these 12 countries corresponds to the mid-point of their group in the severity scale. For example, for the 'moderate' group, with GHI between 10 and 20, we assign 15.


    