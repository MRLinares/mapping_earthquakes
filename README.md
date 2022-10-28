# Mapping Earthquakes

## Overview

Create interactive map of earthquake and tectonic plate utilizing GeoJSON data.

<br>

> ### ***Resources:*** <br>
> **Data:** Earthquakes GeoJSON, M4.5+ Earthquakes GeoJSON, Tectonic Plate GeoJSON\
> **Software:** Virtual Studio Code v1.72.2, HTML/CSS, JavaScript, Leaflet v1.7.1, D3.js v5

## Results

After obtaining an API from Mapbox, I created several folders to house my html, css, and API, and javascript logic.  I created an interactive map with layers and selectable modes.  The selectable modes are Day/Night Navigation, Satellite, and Street.  The map is draggable and can be zoomed in.  The layers are the Earthquake, Major Earthquake, and Tectonic Plate data retrieved from GeoJSON data sources.  I mapped them with circle markers and linestrings, respectively.  These modes and layers can be switched and activated in the top right hand corner of the map screen.  There are examples below.

> Night Navigation map without any layers:
<img width="1721" alt="nightNavigation_noLayers" src="https://user-images.githubusercontent.com/108758105/198707312-21816f16-15b5-4c8f-85f9-8a6784a2b73d.png">
<br>

> Night Navigation map with all layers:
<img width="1725" alt="nightNaviAllLayers" src="https://user-images.githubusercontent.com/108758105/198706290-5db88011-f95b-469c-8f0a-2e96c5ef704a.png">
<br>

> Day Navigation map with teconic plate lines layer:
<img width="1726" alt="dayNavi_tectonic" src="https://user-images.githubusercontent.com/108758105/198706429-c0c83453-49dc-443c-ae45-0f452666ff4b.png">
<br>

> Satellite Streets map with all earthquakes layer:
<img width="1724" alt="satelliteAllQuakes" src="https://user-images.githubusercontent.com/108758105/198706510-68ae8f0b-d18a-4331-82aa-ee9e1b154f6e.png">
<br>

> Street map with major earthquakes (categorized as 4.5 magnitude and higher) within the last 7 days layer:
<img width="1725" alt="streetsMajorQuakes" src="https://user-images.githubusercontent.com/108758105/198706577-fd3217cc-1d02-427f-b5ab-278d081071f3.png">

