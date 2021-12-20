# PYTHON-API-challenge

Python API  - What's the Weather Like?

WeatherPy is a Python script that visualises the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, a Python library, the OpenWeatherMap API, is used to create a representative model of weather across world cities. At least 500 unique cities are randomly selected based on latitude and longitude. A weather check on each of the cities is completed using a series of successive API call, including a print log of each city as it's being processed with the city number and city name. A CSV of all retrieved data and a PNG image for each scatter plot has ben saved.

The following relationships are compared using Scatter Plots:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Linear regression is then run on each relationship, separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

Relationships are explianed after each plot.

VacationPy
A heat map is created that displays the humidity for every city from the part I of the homework. The dataframe is narrowed down based on ideal weather conditions. Goople Places API is used to find the first hotel for each city located within 5000 meters of the city's coordinates. Those hotels are then plotted with the heatmap, including an info box with details about the hotel.

All images are located in the images folder. 
