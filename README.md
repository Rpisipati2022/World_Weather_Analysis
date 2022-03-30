# World_Weather_Analysis
## Overview

Tourism is a fast growing industry, especially post-pandemic as people try to get asway from the confines of their homes. Weather conditions influence choice of where people wish to go on holiday. The purpose of this analysis is to allow a traveler the option of selecting vacation destinations based on their choice of ideal weather conditions.

### Resources Utilized to Complete Analysis
- CSV Files: Weather_Database.csv, WeatherPy_vacation.csv
- Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb
- Python: Python v3.9.7, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

### Weayther data base
A random set of 2,000 latitudes and longitudes were generated, and the nearest cities corresponding to these coordinates were found.  An API call was then made to retrieve the following data for each city:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Current Weather description
This data was stored in a file called city_data_df which looks like this:
<img width="468" alt="image" src="https://user-images.githubusercontent.com/99691015/160731726-2ec60971-5641-4609-a7bf-c037ef69126f.png">

### Vacation Search
The traveler was queried on the minimum and maximum temperature they desired for places they would consider visiting. Based on these inputs, a list of cities that met these criteria was developed from the main data set created above. This was displayed on a map which showcased destinations using pop-up markers on a marker layer-map.

### Sample Travel Destinations
<img width="468" alt="Trvl_Dest" src="https://user-images.githubusercontent.com/99691015/160731866-6b5b8f87-70f2-4c93-88dd-cca23608c2e1.png">

### Vacation Itinerary
Using the Google Directions API, a sample itinerary was created for a trip through four cities in Mexico.
<img width="468" alt="Vac_Iti" src="https://user-images.githubusercontent.com/99691015/160731940-2477a204-bc64-44c1-9ea6-50ae47c129bd.png">
<img width="468" alt="Directions" src="https://user-images.githubusercontent.com/99691015/160732175-0f72cd46-067e-4860-b7df-4884aa6dd531.png">


