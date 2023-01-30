# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goald of the project is to retrieve data using API, perform EDA and finally build a regression model

## Process
1. retrieve bike station, longitude, latitude and number of bikes from city bike API
2. retrieve point of interest (POI) of the restaurants which are located near the bike station from Four Square API and Yelp API. Next, compare the results between the above API
3. Perform EDA and export the results into sqlite3 database
4. Build regression model

## Results
I have chose the new york bike station and found some restaurants which are located near there. However, after performing the EDA, it is quite difficult for me to build a regression model because the correlations between POI and number of bikes in that area are very weak

## Challenges 
1. Loop the longitude and latitude of the city_bike data to find the longitude and latitude of the nearby restaurants
2. Difficult to find a relationships between dependent variable which is the number of bikes with other independent variables
## Future Goals
1. Perform a better EDA
2. Gain more analytical skill and critical thinking from project and from cohort
