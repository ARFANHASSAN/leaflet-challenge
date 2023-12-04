# leaflet-challenge
 ![USGS]("C:\Users\bella\Desktop\leaflet-challenge\Leaflet-Part-1\Images\1-Logo.png")
 
## Background

The United States Geological Survey, abbreviated as USGS, has the crucial responsibility of furnishing scientific data pertaining to natural hazards, ecosystem health, environmental conditions, and the impacts of climate and land-use changes. The scientists at USGS continuously innovate by developing novel methods and tools to provide timely, pertinent, and valuable information concerning the Earth and its various processes.

Currently, the USGS is keen on creating a new suite of tools designed to visualize their earthquake data. Despite collecting vast amounts of data from global sources daily, they lack a meaningful method of presentation. Your challenge is to undertake the development of a visualization solution for USGS data, aiming to offer an improved means for educating the public and other governmental entities. The goal is not only to enhance public awareness but also to attract additional funding to address the pressing issues confronting our planet.
## Instructions
* Part 1: Generate a Visualization for Earthquake Data
* Part 2: Collect and Visualize Additional Data
## Part 1: Generate a Visualization for Earthquake Data
![Earthquake Visualization]("C:\Users\bella\Desktop\leaflet-challenge\Leaflet-Part-1\Images\2-BasicMap.png")
Commence your initial task by creating a visualization for a given earthquake dataset. Follow the outlined steps below:
* Acquire your dataset by adhering to the following steps:
* Access earthquake data from the USGS, available in various formats and updated every 5 minutes. Visit the USGS GeoJSON Feed page and select a specific dataset for your visualization. The provided image serves as an illustrative screenshot of what you will encounter upon visiting the given link:[USGS GeoJSON Feed ](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php )
![]("C:\Users\bella\Desktop\leaflet-challenge\Leaflet-Part-1\Images\3-Data.png")
* Upon selecting a dataset, like "All Earthquakes from the Past 7 Days," you will be presented with a JSON representation of the data. Utilize the URL of this JSON to retrieve the necessary data for your visualization. The provided image offers a glimpse of earthquake data presented in JSON format: 
![]("C:\Users\bella\Desktop\leaflet-challenge\Leaflet-Part-1\Images\4-JSON.png")
## Import and visualize the data by performing the subsequent actions:
* Employing Leaflet, construct a map that plots all the earthquakes from your dataset, utilizing their longitude and latitude coordinates.
* Configure your data markers to mirror the earthquake magnitude through size and earthquake depth through color. Ensure that earthquakes with higher magnitudes appear larger, while those with greater depth exhibit a darker color on the map. This approach provides a visual representation that correlates marker characteristics with the key seismic attributes of magnitude and depth.
* Hint: The depth of the earth can be found as the third coordinate for each earthquake.
* Enhance user interaction by incorporating popups that furnish additional information about each earthquake when its corresponding marker is clicked. This feature adds a layer of detail and context to the visualization, offering users a more comprehensive understanding of individual seismic events.
* Create a legend that will provide context for your map data.
* Your visualization should look something like the preceding map.