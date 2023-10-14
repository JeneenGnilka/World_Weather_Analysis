# World_Weather_Analysis
Part 1 - WeatherPy
  the code required to generate random geographic coordinates and the nearest city 
  to each latitude and longitude combination is provided.

  Use the OpenWeatherMap API to retrieve weather data for the cities list generated with the starter code.
  Create a series of scatter Plots showing the relationship between weather variables and latitude
    - Latitude vs Temperature
    - Latitude va Humidity
    - Latitude vs Cloudiness
    - Latitude vs Wind Speed

  Compute linear regression for each relationship
    - Define a function to create the linear regression plots
    - create a series of scatter plots - include the linear regressionline, the model's formula and the r values
    - Create the following plots:
        - Northern Hemisphere: Temperature vs Latitude
        - Southern Hemisphere: Temperature vs Latitude
        - Northern Hemisphere: Humidity vs Latitude
        - Southern Hemisphere: Humidity vs Latitude 
        - Northern Hemisphere: Cloudiness vs Latitude
        - Southern Hemisphere: Cloudiness vs Latitude
        - Northern Hemisphere: Wind Speed vs Latitude
        - Southern Hemisphere: Wind Speed vs Latitude
    After each piar of plots, describe any relationships between the latitude and the other weather variables
Part 2
  The code needed to import the required libraries and load the CSV file with the weather and coordinates dat
  a for each city created in Part 1 is provided.

  Create a map that displays a point for every city in the city_data_df with the size of the point being the 
  humidity of each city
  Filtered the data in the city_data_df for Max Temp between 21 and 24 degrees celisus and humidity between 40% and 80%
  Created new DataFrame containing City, Country, Lat, Lng, and Humidity and added an empty column Hotel Name
  Used Geoapify API to find the first hotel located within 10,000 metres of the coordinates and add to the Hotel Name column
  Create a map that displays the cities in the hotel_df dataframe and include Hotel Name and Country to the hover message
  
