# World_Weather_Analysis

### Weather Database
After randomly generating a set of 2,000 latitudes and longitudes, I retrieved the nearest city to each set and performed an API call on the OpenWeatherMap. I created a DataFrame that displays each City, its Country, Lat/Lng, Max Temp, Humidity, Cloudiness, Wind Speed, and Current Weather Description.

### Vacation Search
Using the DataFrame from Weather Database Deliverable 1 and input from the user's weather preferences (min temp and max temp), I found cities that meet the user's preferences and mapped them out with nearby hotels. 

### Vacation Itinerary 
I picked one country (Egypt) that had four cities with the user's temperature preferences. I created a route to get from the starting location to stops 1, 2, and 3 and then back to the starting location. In addition to providing a route for the user, a second map was created to show weather conditions and a nearby hotel in each city.