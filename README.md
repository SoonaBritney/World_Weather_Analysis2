# World_Weather_Analysis


Overview
The World Weather Analysis project is utilizing Python skills combined with Open Weather Map API and Google Map API to create the below: 
1: Retrieve Weather Data
2: Create a Customer Travel Destinations Map
3: Create a Travel Itinerary Map

1: Retrieve Weather Data
1) Step 1: We generated random 2, 000 latitude and longitude combinations by using Python NumPy function.
2) Step 2: We ran the random 2,000 coordination via open weather map API to retrieve Latitudes, Longitudes, Max Temperature, Humidity, Cloudiness, Wind Speed, Country, and current weather Description. 
3) Step 3: We saved the data into data frame and exported to as WeatherPy_Database.csv file.

URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Weather_Database.ipynb
Output URL:https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Weather_Database/WeatherPy_Database.csv



2: Create a Customer Travel Destinations Map
1) Step 1: We utilized the WeatherPy_Database.csv above to tart with 2,000 city data.
2) Step 2: We created the input feature to prompt the user to enter minimum and maximum temperature criteria to narrow down the travel itinerary criteria. For example, if the preferable search criteria is between the maximum 99 F and 66 degree, the preferable city list became 848 among 2,000.
3) Step 3: We used the Google Maps API, created the preferable city world map with heat layers, and markers, which display the hotel name, city, country, and maximum temperature to help users to search their itinerary. 

URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Search/Vacation_Search.ipynb
Output URL:https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Search/WeatherPy_vacation.csv
Map Image:https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG


3: Create a Travel Itinerary Map
1) Once users pick 4 destinations, we draw the destination from start to end map using google maps API. 
2) We could add the travel direction, travel mode on the map, such as "DRIVING", "BICYCLING", or "WALKING" to help users.
3) We could add markers on the destination map to visualize the information.  

URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb
Map Image URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Itinerary/WeatherPy_vacation_map.PNG
Itinerary Map Image URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG
Hotel Map with Markers URL: https://github.com/SoonaBritney/World_Weather_Analysis2/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG

Conclusion
1) It is very helpful to use the "Open Weather Map API" to utilize the existing rich data into our world weather analysis. 
2) It is very helpful to use the Google Maps API to visualize the city information, travel planning, and directions, so on.
 
