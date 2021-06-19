# python-api-challenge
# What's the Weather Like?

#Background
This file answers the fundamental question: "What's the weather like as we approach the equator?"

# Part I - WeatherPy 
  (The folder "WeatherPy" has all the analysis related)
  
Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Utilized a simple Python library and the OpenWeatherMap API to create a representative model of weather across world cities.

Created a series of scatter plots to showcase the following relationships:

    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude

After each plot, added a sentence or two explaining what the code is analyzing.

Ran linear regressions on each relationship. This time, separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

      Northern Hemisphere - Temperature (F) vs. Latitude
      Southern Hemisphere - Temperature (F) vs. Latitude
      Northern Hemisphere - Humidity (%) vs. Latitude
      Southern Hemisphere - Humidity (%) vs. Latitude
      Northern Hemisphere - Cloudiness (%) vs. Latitude
      Southern Hemisphere - Cloudiness (%) vs. Latitude
      Northern Hemisphere - Wind Speed (mph) vs. Latitude
      Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, explained what the linear regression is modeling. 
Saved a CSV of all retrieved data and a PNG image for each scatter plot in output_data folder.

# Part II - VacationPy
Working with weather data to plan future vacations.

Created a heat map that displays the humidity for every city from Part I.
Narrowed down the DataFrame to find ideal weather condition. Drop any rows that don't contain all three conditions. 
Used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
Included screenshots of the heatmap created in the Images folder.
