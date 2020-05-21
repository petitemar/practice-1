# practice-1

The goals for this tutorial are:

To explore GeoJSON data, and how geographical features on our earth translate to projected shapes on an svg.
To understand projections, in conjunction with d3.geo-path, transforms lattitude and longitude space into pixel space.
To grasp that d3.js svg maps are as simple as lines and circles, and can be manipulated as such, with stroke, fill, etc.
To be exposed to the concept of something updating with every mouse movement -- the early stages of what will later become a tooltip.

ASSIGNMENT:

Implement your own version of the map, using the us state geojson data provided in the data folder, or another geojson of your choice.

 Using your own lat/long dataset OR the provided dataset for this exercise, usHeatExtremes.csv (also in the data folder), add points to your map. HINT: since we're still in svg, we can just add circles to the map, like we've done before, but you'll need to use your projection to translate from (long,lat) values to (x,y) values.

 Add mouseover behavior to each point, so its data updates state, and is displayed in our tooltip display.

 Make intentional design decisions -- colors, sizes, axes, transitions, etc. should illustrate something interesting about or relevant to your data.
 
 
 Resources:
 
d3 geo

© 2020 GitHub, Inc.
