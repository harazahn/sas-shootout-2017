# sas-shootout-2017
Final project for STA 6704 (Data Mining II)

## Data
[SAS Shootout 2017 Data](http://www.sas.com/events/analytics/us/2017-analytics-shootout-data-package.zip)

Contains the following files:

Name | Size
---- | -----
drought_severity.sas7bdat | 209 MB
drought_severity_scoring.sas7bdat | 21.8 MB
LandCover_by_County.csv | 236 KB
NOAA_Zones_to_Counties.csv | 351 KB
population_by_county_2001_2009.csv | 328 KB
population_by_county_2010_2015.csv | 268 KB
Shootout 2017 Data Dictionary.pdf | 320 KB
Shootout 2017 Problem Statement.pdf | 640 KB
storm_events.sas7bdat | 236 MB
storm_events_scoring.sas7bdat | 15.1 MB
US_weather_stations_counties.csv | 2.87 MB
weather_station_data.sas7bdat | 4.12 GB
weather_station_scoring.sas7bdat | 317 MB
wildfire_events.sas7bdat | 1.43 MB
wildfire_narrative.sas7bdat | 113 MB

## Modeling Tasks

### Wildfire Conditions :fire:
Conditions for wildfires change based on a number of factors. At any particular time and location, given a cause, the chances of a wildfire occurring will change. Using any of the data provided, develop a model for predicting propensity of wildfire at any given time based on the current conditions at that same time. What type of model techniques did you find effective? What are the conditions most favorable for a wildfire?

### Wildfire Causes :fire:
A fire cannot start without cause (spontaneous combustion, spark, etc.). Sometimes it can start from a natural event. Other times is can be linked directly to human activity. The cause of a wildfire is often determined after the event has occurred. Using the data provided and the “Wildfire Narratives”, extract additional information that may help classify wildfires by cause. For example, how often are you able to determine the initial cause of a wildfire? Produce a model that will predict the probability of potential causes of a wildfire by time and geography.

### Wildfire Impacts :fire:
The “impact” of a wildfire can be defined in many ways, including area burned, people displaced, cost to contain, cost in damage, and lives lost. Impacts vary greatly based on the cause, the physical geography, and the weather conditions before and after ignition. In the data provided, the impact of the wildfire events is not always captured adequately in the variables. Using the “Wildfire Narratives”, extract additional information to help quantify how impactful the wildfires are in terms of acres burned. Build a model that predicts acres burned from the provided variables.
