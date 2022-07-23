# **World_Weather_Analysis**
---
## **Overview of Project:**

The project’s objective is to improve a travel app to give customers a way to decide their travel destination and ideal hotel based on weather preferences. The work is in three folders: Weather_Database, Vacation_Search, and Vacation_Itinerary. 

--- 
## **Resource:**
**Data Sources:** 

**CSV Files:** [WeatherPy_database.csv](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_database.csv), [WeatherPy_vacation.csv](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv), 

**Jupyter Notebook Files:** [Weather_Database.ipynb](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), [Vacation_Search.ipynb](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb), [Vacation_Itinerary.ipynb](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb).

**Images:** [WeatherPy_vacation_map.png](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png), [WeatherPy_travel_map.png](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png), [WeatherPy_travel_map_markers.png]()

**Software:** Anaconda 4.13.0, Jupyter Notebook 6.4.11, Python v3.8.9

**Dependencies:** Pandas, Numpy,  Matplotlib, Matplotlib.pyplot, CitiPy, Datetime, Requests, Gmaps, APIs, JSON Traversal, SciPy.

--- 
## **Summary:**

The Weather_Database folder contains the Weather_Database.ipynb and WeatherPy_database.csv, a set of 2,000 random latitudes and longitudes was generated, and an API’s call was made to OpenWeatherMap for current weather data for the nearest corresponding cities. Retrieving the latitudes, longitudes, maximum temperature, wind speed, current weather description, percent humidity and cloudiness. 

The Vacation_Search folder contains the Vacation_Search.ipynb, WeatherPy_vacation.csv, and WeatherPy_vacation_map.png.The customers can identify potential destinations and nearby hotels based on weather preferences, using gmaps and adding pop-up markers on a marker layer map. 

![WeatherPy_vacation_map.png](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


The Vacation_Itinerary folder contains the Vacation_Itinerary.ipynb, WeatherPy_travel_map.png, and WeatherPy_travel_map_markers.png. The following itinerary travel maps were created using Google Directions API showing  the route between four cities in Canada. 

![WeatherPy_travel_map.png](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

The pop-up markers show the Hotel name, City, Country, and Current weather description with the maximum temperature in degrees Fahrenheit. 

![WeatherPy_travel_map_markers.png](https://github.com/bishopce16/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
