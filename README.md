# U.S. Atlantic Hurricane Landfalls

## About the Map
This map displays every Atlantic hurricane landfall in the U.S. from 1851-2026. The map was created as part of a web mapping class lab project and is designed to provide an interactive overview of the hurricane landfall locations, along with other important information for each hurricane - with name and category displayed in each tooltip when hovering over the hurricane symbol, and more information displayed if clicking on it.

## Map Features
The web map includes:

- Every Atlantic hurricane landfall in the U.S. from 1851-2026, denoted by hurricane symbols/icons that vary in color based on the storm category (Saffir-Simpson Scale)
  
- A choropleth layer that shows the total number of landfalls for each state
  
- An interactive Leaflet basemap
  
- Tooltips that pop up upon hovering over or clicking on a hurricane icon, showing important storm information

## Methods
The web map was created using HTML, CSS, and JavaScript, with the Leaflet JavaScript library used to create the interactive map and the font awesome library used for the hurricane symbols. The hurricane data was gathered from NOAA through their data page. The data is called HURDAT2 best-track data.

Leaflet was used to display the hurricane symbols and provide the interactive mapping functionality, while HTML and CSS were used to structure and style the web page.

## Data Sources
The Hurricane Landfall Data was gathered via NOAA: [NOAA Data Page](https://www.nhc.noaa.gov/data/)

The basemap was found through [Leaflet Provider Demo](https://leaflet-extras.github.io/leaflet-providers/preview/) and is from ESRI.
