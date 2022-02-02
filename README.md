# World_Weather_Analysis

### Overview
Working with Jack on the PlanMyTrip app, we've worked on some new changes if we can make it through this round of Beta testing, we will be ready to take this app to the stratosphere!  We can plan on clear skies, if we map out our destination accordingly.  

## Deliverable One
**First, we need to retrieve the data we're going to be working with from the API call, we'll be looking at:**
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description (i.e.: clouds, fog, light rain, clear sky)

![APIcode](images/APIcode.PNG) 
![APIimage](images/APIimage.PNG)   

**Next, we'll add that data to a DataFrame:**

![city_df](images/city_df.PNG)   

**We will then export our DataFrame as WeatherPy_Database.csv into the Weather_Database folder, where we'll be able to continue our work from there!**

![csv](images/csv.PNG)  

## Deliverable Two
**We're ready to see if this app will work with our customer's needs, let's check and see if the input statements are written to prompt the customer for their minimum and maximum temperature preferences.**

![minmax](images/minmax.PNG)    

**Create a new DataFrame based on the minimum and maximum temperature, and empty rows are dropped.**

![preferred_cities_df](images/preferred_cities_df.PNG)  
 
**The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.**

![hotel](images/hotel.PNG)

**The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as Vacation_Search.csv.**

![csv2](images/csv2.PNG)

**We've created a marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:**
- Hotel name
- City
- Country
- Current weather description with the maximum temperature

**Let's make sure it's showing our clients what they want to see!**

![layer_map](images/layer_map.PNG)

## Deliverable Three
**Now let's map out a 4 city itinerary for our client and put this app to the test! Creating a DataFrame that shows each of our four cities.**

![itinerary_df](images/itinerary_df.PNG)    

**The latitude and longitude pairs for each of the four cities are retrieved.**

![latlng](images/latlng.PNG)  

**A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. What an adventure our clients will have zipping from city to city!**

![zip](images/zip.PNG)

**A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:**
- Hotel name
- City
- Country
- Current weather description with the maximum temperature

**Book me at the Hotel Por do Sol, the weather looks incredible!**

![markers](images/markers.PNG)

## SUMMARY
After working through another run with Jack on the PlanMyTrip app, we are pleased with how the tool is perfoming.  Our outlook is sunny, and we anticipate fair winds in our business venture. Not a cloud in sight.






