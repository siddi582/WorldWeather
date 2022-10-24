# World Weather Analysis
Project Overview
In this project, we will practice your analysis, visualization, and statistical skills by retrieving and analyzing weather data for a hypothetical travel company PlanMyTrip.

#### Resources
Data Source: https://openweathermap.org/api, https://console.cloud.google.com/apis
Software: Jupyter Notebook, Pandas Library, CityPy, Python Request, APIs, JSON Traversals, Google Maps 

Summary
In this projects, using API's we generated 2000 random Latitude and Longitude coordinate pairs across the world. We then found the closest city to each of those coordinate pairs. We then retrieved, collected, and cleaned weather data from each city coordinate pair. The weather data was then used to help prospective vacationers find a city and hotel that meet their weather preferences. We then added weather description to the weather data. Weather presences were added to identify ideal travel destinations and hotels nearby. Four cities were chosen to create a travel itinerary. Using Google Maps Directions API, a travel route was created between those four cities and a marker layer was added to the map.

#### Retrieving Weather Data
A set of 1500 random Latitude and Longitude coordinates was created. Then a list of cities were created by using the coordinate pairs and finding the nearest city to each pair. By doing this, we found 616 cities.

![image](https://user-images.githubusercontent.com/111712209/197503186-b5b8da71-d975-4f7a-aa5f-5cffb74755b8.png)
