# World_Weather_Analysis

## Overview
The purpose of this analysis is to use APIs to filter weather data and map data to plan trips based on preferences.

## Weather Analysis
We first gathered 1,500 random cities throughout the world and used OpenWeatherMap API to request current weather.  We collected the pertinent data on each city including:
- City
- Country
- Date
- Latitude
- Longitude
- Maximum temperature
- Humidity
- Cloudiness
- Wind Speed

We compared and observed the correlations in the latitude and weather data using scatter plots and linear regression.  We also used heatmaps to view the comparison between latitude and the weather data.

## Travel Data
We then used this weather data in addition to the Google Maps Places API to assist in the planning of travel.  We used input for the desired minimum and maximum temperatures and used this data to select cities within that range.  We then collected nearby hotel information on the cities.  We provided a map displaying the cities and added pop-up markers with the hotel and current weather information.

## Trip Itinerary
We used Google Maps Directions API to plan a trip with driving directions for our four selected cities.  This map also includes pop-up markers with hotel and current weather conditions.  An image of the map can be seen below.
![alt_text](https://github.com/bweirich/World_Weather_Analysis/blob/main/Vacation_Itenerary/WeatherPy_travel_map.png)