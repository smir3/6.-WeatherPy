# WeatherPy-
Plan my trip is a top travel technology company, specializes in internet related services in the hotel and lodging industry. Jack is the head of analysis for the user interface team. He has asked you to help him collect and present data to customers via the search page which they will then filter based on their preferred travel criteria, in order to find their ideal hotel anywhere in the world. To perform this task you will be using the jupyter notebook in the city py module to get the cities for more than 500 random latitudes and longitudes, then you will perform request on the open weather api and retrieve the weather data from these cities. The weather data will be added to a pandas dataframe where you will use matplotlib to create a series of scatterplots to show the relationship between latitude and a variety of weather parameters for over 500 cities around the world. As part of the analysis will need to perform statistical analysis on the data using linear regression on the weather paramters in the northern and southerm hemispheres. This data will help the team predict the best time of year for people to plan their vacation. Finally will export the data, clean it, and use the weather data to choose the best cities for vacation based on certain weather criteria. And map these cities using jupyter g maps, nad google places API. Help travellers find their ideal vacation spot.

Basic Project Plan
Here's an outline of your project plan:

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
Your analysis of the data will be split into three main parts, or stages.

Collect the Data

Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization

Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Store the name of the first hotel in the DataFrame.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
