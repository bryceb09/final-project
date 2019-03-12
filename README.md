# Final Project 

## General Information

Created by Dean McNamee and Marcin Ignac, [9.5](http://www.ninepointfive.org/) is a web map that utilizes WebGL to explore earthquakes over the past 30 years. The targeted audience is the general public and anyone who is interested in seeing earthquake data visualized. Basic functions of 9.5 include selecting lines, particles, and rings. Users are also able to change the magnitude, position the sun, and take a tour of a selected point.


## System Architecture

## Critique

9.5 offers a sleek and user-friendly UI that is visually appealing with easy to use operational features. The color scheme used is consistent and adds an earthy tone to the web map. The front page text is easy to read and provides crucial information about what the objective is, the creators, and data source. Once an earthquake is selected then there is a wall of text which describes when, where, magnitude, number of casualties, number of infrastructure affected, and damages in the surrounding area. 9.5 does feature an about page but that is a sperate URL which can’t be accessed from the main page. The position of the text while is out of the way makes it hard to view all the text due to the small font size. The ability to change from light to dark adds a nice visual contrast allowing the viewer to see each earthquake location in different lighting. Legibility is clear, there is no typoes found, and incldues a clear hierarchical origination ranging from earthquakes with the highest magnitude all the way down to earthquakes with the lowest magnitudes. 9.5 also does not feature responsive design leaving which only makes it viewable on a computer. Overall, 9.5 is a well put togther web map that offers clear visuals, user friendly features, and a plethora of information about each earthquake.  

## Data Sources

* [NASA](https://earthobservatory.nasa.gov/features/BlueMarble)
  * raster-tilelayers (JPG)
  * raster-tilelayers (PNG)
* [U.S. Geological Survey](https://earthquake.usgs.gov/earthquakes/)
  * vector

## About Basemap, Thematic Layer, and Interactive Features

9.5 utilizes a satellite basemap of earth with tile layers from NASA. The thematic layer offered is a transistion from light to dark via the Day/Night featue. Interactive features include:
* Year/Month Slider
* Magnitude Slider
* Day/Night Slider
* Option to set lines, particles, or rings
* Tour Feautures
* Supersampling Toggle
* Selectable Earthquake with Zoom and Pulsate Feature
* Links to Data Sources and Creators

## Web Map Elements

* Interactive Legend
* Creator Label
* Data Source Label

## Recommendations

9.5 is a fun interactive map that allows the viewer to get a first-hand look at where the earthquake took place, the magnitude, and a description of the total destruction caused. 9.5 offers great interactive elements such as the year/month slide and the ability to select a specific earthquake to view. The use of WebGL brings a 3D aspect to the map which adds a new spin on a classic earthquake map. My recommendations would include adding a link to the about page and creating a pop-out text box for the data descriptions of each earthquake. The text on each description is long but having it in a small area with a small font size makes it difficult to read. Aside from those recommendations I thoroughly enjoying 9.5 and believe it is a well put together web map. 
