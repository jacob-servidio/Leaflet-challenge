# Leaflet-challenge
Leaflet Homework - Visualizing Data with Leaflet

United States Geological Survey, or USGS, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

Build a new set of tools that will allow the USGS to visualize their earthquake data. The USGS collects a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

• The data is sourced from U.S. Geological Survey (USGS) site, the USGS provides earthquake data in different formats, updated every 5 minutes. On the USGS GeoJSON Feed page and when you click on 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data.

• Imported & Visualized the Data.

• Created a map using Leaflet that plots the earthquakes from data set based on their longitude and latitude.

• Data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

• Included popups that provide additional information about the earthquake when a marker is clicked.

• Created a legend that will provide context for your map data.

In order to run these files locally, run a local python server with the following line of code.
python -m http.server 8000 --bind 127.0.0.1
