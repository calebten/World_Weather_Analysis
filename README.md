# World_Weather_Analysis

## Overview

This project includes uses openweather API and Google Maps API and has three parts.

* Weather_Database: This section randomly creates 2000 lattitudes and longitudes and uses citypy module to get the nearest city. It then uses the open weather API to retrive the weather for the cities and stores it datafarme and CSV
* Vacation_Search : This section asks the user for their temprature preference for vaction and filters the weather database created in the above section based on the preference. It then uses google maps API to retrive the hotels in the city and displays the first  hotel wlong with weather data and city details on a market on google maps
* Vacation_Itinerary : This section selects four cities from  map displayed in the previous section and uses google maps directions api to display the route between the four cities aong with the marker details
