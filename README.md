# First Commit- python-api-challenge

# Part 1: WeatherPy
Python script to visualize the weather of over 500 cities of varying distances from the equator-starter code with the required libraries.  
Used  citipy Python library to generate the city list  
Used the OpenWeatherMap API to retrieve Location data (Lat, Long) weather data (Max Temp, Humidity, Cloudiness import the required libraries , Wind Speed)from the cities list generated in the starter code  
Saved results in a list and converted it to DataFrame  
Saved data in a csv file(cities.csv) in the output_data folder  
Created Scatter Plots to Showcase the Relationship Between Weather Variables (Max Temp, Humidity,Cloudiness, Wind Speed )and Latitude  
Created a function to show the linear regression between each of these relationships and included the linear regression line, the model's formula, and the r^2 values  
Filtered city data in Northern and Southern Hemisphere  
Called the linear regression plot function for each relationip for both hemispheres  
Described the linear relationship for each relationship plotted  


# Part 2: VacationPy
Starter code needed to import the required libraries and load the CSV file(cities.csv) with the weather and coordinates data for each city created in Part 1.  
Created a map that displays a point for every city, with the size of the point based on the humidity in each city, in the city_data_df DataFrame.  
Filtered the city_data_df DataFrame to my ideal weather conditions-A max temperature lower than 27 degrees but higher than 21,Wind speed less than 4.5 m/s, and Zero cloudiness.  
Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.  
For each city, used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates.  
Imported hv.extension('bokeh') to display hover box on each point on map.  
Added the 'Lng', 'Lat','City', 'Humidity','Hotel Name', 'Country' information in the hover message for each city on the map.  

# Note
Please note that the regression equatios in the discussion section are the ones that were returned in my final run. These are likely to change slightly as is the case with regression models in every fresh run.
