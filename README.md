# Module 6 Challenge - Data-Visualization
This repo contains the files for the Module 6 challenge assignment.

The folder, "WeatherPy", contains:

1. Two Jupyter notebooks, 
- "WeatherPy.ipynb"
    - Generates a set of ~600 random latitude and longitude coordinates then calls the OpenWeatherMap API to obtain weather data for those cities (as available). The resulting dataset, "cities.csv" is stored in the "output_data" folder.
    - Creates scatter plots of various weather conditions by latitude and makes observations by Northern and Southern Hemispheres for cities in "cities.csv". Images are stored in the "output_data" folder.
- "VacationPy.ipynb"
    - Utilizes the HoloViews plotting tool to create a world map of cities in "cities.csv", showing the location of the cities and illustrating humidity by the relative size of the point on the map.
    - Narrows the dataset to 10 cities having the most ideal weather conditions and calls the Geoapify location platform to obtain the first hotel within 10,000 meters of the city's coordinates. The locations and hotel information are plotted on a world map.
2. A folder labeled "output_data" contains the above-mentioned files:
    - "cities.csv" - data set of city information for ~600 randomly generated coordinates.
    - Scatter plot and linear regression figures showing various weather conditions by latitude.