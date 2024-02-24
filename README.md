# python-api-challenge

This is a repository using Python requests and APIs to solve weather-related questions and problems.  The deliverables are in two parts.  The first part (WeatherPy) uses the cityPy Python library and the OpenWeatherMap API to answer the question "What is the weather like as we approach the equator?" and create representative models of weather across cities.  The second part (VacationPy) identifies ideal vacation spots based on chosen weather parameters and finds the closest hotel to those cities using the Geoapify API.

The repository contains a README file, a gitignore for the API keys, a CSV file called cities.csv containing weather data for 500 cities, and a folder called WeatherPy containing two Jupyter Notebook files called VacationPy and WeatherPy which contain all of the code for the data cleaning and visualization, and a Python file that stores the API keys used to create the city data for the plots in VacationPy and WeatherPy.

In WeatherPy linear regression scatter plots were created and analysis was performed on the relationships between the Northern and Southern hemispheres and the specific weather categories of temperature, humidity, cloudiness, and wind speed.


In VacationPy a map was created displaying the points for every city in the city_data_df DataFrame and the DataFrame was narrowed down to specific parameters around temperature, humidity, cloudiness, and wind speed.  The Geoapify API was used to find the first hotel within 10,000 meters of the coordinates for each city in the new DataFrame.  A map with the selected cities was created with the hotel name and country added into the hover message for each city.
