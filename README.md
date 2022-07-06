# Newport-Historic-Spring

## Data Topic:
The map itself is based around displaying what artifacts have been found at an archaeological site in Newport, Rhode Island. A nonprofit organization, the Church Community Housing Corporation, seeks to turn the historic spring site into a public park and hired archaeologists to excavate and analyze the area before implementing the park. For three years, my professor has volunteered at the site and has excavated a number of artifacts each year, within the grid system that they have been working in. My professor would love to be able to display what has been found throughout the site over the years and supported my endeavors in this project by supplying me with her data.

## Map Objectives:
The objectives of the map are to display the different types of artifacts within the grid system over the span of three years spent excavating. The map will help in interpreting the site and aid in explaining some of the analysis to the public.

## User Needs:
An archaeologist decides to dig at an old housing site in Massachusetts and comes across some artifacts. Questioning whether they should be finding some of the materials, they decide to look up background information on the Newport Historic Spring due to similar time periods. On the website, a link to a map of the archaeological dig pops up and they are taken to an interactive map that allows them to see where and what artifacts were found over the three years of the dig.  

## Data Sources:
My professor gave me a catalouge of the data that she has collected over the three years at her site and I have reduced the information into a CSV (find in the data folder) and used some of the information from the newport Historic Spring website in discussing the project (https://newportspring.org/). 

## Methods of Representation:
The map is in the form of a choropleth, that showcases where most of the artifacts were found so that interpretations can be made, and the artifacts are classified based on type (glassware, porcelain, faunal remains, pipe stem). 

## User Interface:
The map allows one  to select what type of artifact to view on the right handside of the map, which in turn displays where on the grid map such artifacts were found and how many if they hover over a specific grid.

## Technology Stack:
I utilized QGIS to help in creating polygons for the map, based on the coordinates collected onsite by my professor, and I used mapbox studio to help in displaying my map as well. I stored my data in a CSV file as well as a GeoJSON file and used Leaflet as a JS library for displaying the map. I also used HTML, CSS, and bootstrap to help in styling the webpage as well as the map. And ultimately, I hosted my map on GitHub pages.