## Context:
## Potentially interesting source of correlation is between weather and crime, we wanted to explore as weather get colder or warmer how crime number varies.

## Content: 
## Data Source
## Crimes in Chicago Data from kaggle: https://www.kaggle.com/currie32/crimes-in-Chicago
## Hourly Weather data from Kaggle: https://www.kaggle.com/selfishgene/historical-hourly-weather-data#temperature.csv
## Acknowledgements: The dataset was acquired using Weather API on the OpenWeatherMap website, and is available under the ODbL License.

## Both Data File is in CSV format.

## Loaded Chicago crime file and removed any null value.
## We selected year 2015 for our exploration.
## Created filtered dataframe from specific columns
## Rename the column headers
## Transformed datetime into date
## Did groupby by number of crimes along with date and primary type of crime.


## Loaded Weather data file and removed any null value.
## Created filtered dataframe from specific columns
## Rename the column headers
## Transformed datetime into date
## parse the year from date column
## We selected year 2015 data to go with our crime data.
## we wrote and used the function in order to convert temperature data from Kelvin to Fahrenheit.
## Found the avg. temperature by doing groupby 

## postgres
## Create database connection using postgres sql 
## Created database called chicago.db along with tables
## Loaded DataFrames into database
## Joined two tables in postgres,run the queries in postgres

## By doing above steps we were succesfully able to connect crime and temperature data, for each day of year 2015.