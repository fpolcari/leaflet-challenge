# leaflet-challenge
The United States Geological Survey, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

Our first task was to visualize an earthquake dataset.  To do so, we followed the steps below:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php FeedLinks to an external site. page and choose a dataset to visualize.

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. We used the URL of this JSON to pull in the data for the visualization. 

Then we import and visualized the data by doing the following:

Using Leaflet, created a map that plots all the earthquakes from our dataset based on their longitude and latitude.

The data markers reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color. Also, includes popups that provide additional information about the earthquake when its associated marker is clicked.
Finally, created a legend that will provide context for our map data.
