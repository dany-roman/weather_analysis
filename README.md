# Weather_Analysis
**Objective 1** 

Python script to visualize weather of over 500 cities across the world based on their distance from the equator.

**Methods**

- Randomly created 1500 latitude and longitude pairs
- Used CitiPy to find the closest city to the random coordinate pairs
- Deleted duplicate locations
- Iterated through 1500 locations to find weather data [Temperature, Humidity, Cloudiness, Wind Speed] using OpenWeather API
- Created a dataframe from the weather results
- Export clean weather/city dataframe

**Analysis**

Graphed the following:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude
- Northern Hemisphere - Temperature (F) vs. Latitude (linear regression)
- Southern Hemisphere - Temperature (F) vs. Latitude (linear regression)
- Northern Hemisphere - Humidity (%) vs. Latitude (linear regression)
- Southern Hemisphere - Humidity (%) vs. Latitude (linear regression)
- Northern Hemisphere - Cloudiness (%) vs. Latitude (linear regression)
- Southern Hemisphere - Cloudiness (%) vs. Latitude (linear regression)
- Northern Hemisphere - Wind Speed (mph) vs. Latitude (linear regression)
- Southern Hemisphere - Wind Speed (mph) vs. Latitude (linear regression)



**Results**

- There is a linear trend between temperature and latitude.
- There is no observable trend between latitude and humidity, cloudiness, and wind speed.
- There is a strong negative linear correlation between increasing latitude and temperature in the northern hemisphere
- There is a strong positive linear correlation between increasing latitude and temperature in the southern hemisphere
- There is no linear correlation between latitude and humidity, cloudiness, and wind speed in the northern and southern hemisphere.



**Objective 2** 

Find the closest hotel in the cities with my preferred weather conditions



**Methods**

- Import city weather csv file
- Create a humidity map using google maps
- Narrow down data set using preferred weather conditions
- Find the closest hotel to city coordinates using Google Places API
- Display hotel information on Google Maps with humidity layer



**Results**

There are 15 cities with my preferred weather conditions (cloudy, breezy, moderately warm/cool, less than 60% humidity). 



