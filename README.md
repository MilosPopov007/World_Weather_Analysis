# World_Weather_Analysis
Analyzing and presenting data to the customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world.

To perform this task OpenWeatherMap API (An application programming interface ) and  Geoapify API was used along with  Jupyter Notebook (the CitiPy module) and GeoViews (Python library that makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets). 

## Analysis
In [WeatherPy](https://github.com/MilosPopov007/World_Weather_Analysis/blob/main/WeatherPy.ipynb) Jupyter Notebook and the CitiPy module was used to get the cities for  1500 random latitudes and longitudes.Requests were performed on the OpenWeatherMap API to retrieve JSON weather data from these cities. The weather was added added to a Pandas data frame, where  Matplotlib was used to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for more than 500 cities around the world.

[Weather_Database](https://github.com/MilosPopov007/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb) Several tasks where preformed :

*  np.random.uniform function was used to generate a new set of 2,000 random latitudes and 2,000 longitudes.
*  citipy module to get the nearest city for each latitude and longitude combination.
*  OpenWeatherMap's API key was imported ( assembled the API call URL as a string variable ).
*  Retrieve the following information from the API call: ( Latitude and longitude, Maximum temperature, Percent humidity, Percent cloudiness, Wind speed, Weather description (for example, clouds, fog, light rain, clear sky). 
*  Add the weather data to a new DataFrame.



[Vacation_Search](https://github.com/MilosPopov007/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb). Using GeoViews and sorting data frames with user input we were able to present hotel locations based on user ideal temperature input. 

Geoapify API (GeoViews) was used to create a Customer Travel Destinations Map. 

![This is an image](https://github.com/MilosPopov007/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)




