# World_Weather_Analysis
Analyzing and presenting data to the customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world.

To perform this task OpenWeatherMap API (An application programming interface ) and  Geoapify API was used along with  Jupyter Notebook (the CitiPy module) and GeoViews (Python library that makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets). 

## Analysis
In [WeatherPy](https://github.com/MilosPopov007/World_Weather_Analysis/blob/main/WeatherPy.ipynb) Jupyter Notebook and the CitiPy module was used to get the cities for  1500 random latitudes and longitudes.Requests were performed on the OpenWeatherMap API to retrieve JSON weather data from these cities. The weather was added added to a Pandas data frame, where  Matplotlib was used to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for 1500 cities around the world.
