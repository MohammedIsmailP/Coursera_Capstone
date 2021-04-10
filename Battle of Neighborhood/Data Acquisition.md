# Data Acquisition

Following are the data and their respective data sources for our projects are discussed below,

1. Chennai city's major areas and neighborhood

  **Data Source:** [Wikipedia](https://en.wikipedia.org/wiki/Areas_of_Chennai)

  **Data description:** We will initialize crawler to scrape and extract data and information about the areas and locality from the wikipedia web page.

2. Geographical coordinate of the areas

  **Data Source:** Python's [geocoder library](https://geocoder.readthedocs.io/index.html)

  **Data description:** Geocoder is a simple and consistent geocoding library written in Python. Dealing with multiple different geocoding provider such as Google, Bing, OSM and many more. Specifically, we will be using ArcGIS, as it is reliable and free.

3. To get nearby venues in each locality of Chennai city,

  **Data Source:** [Foursquare API](https://foursquare.com/)

  **Data description:** This API allows us to get information about all the venues in the neighbourhood of Chennai City. Foursquare Credentials is used to fetch the data.