# Walkability analysis
An exercise at mapping sidewalks and pedsheds in Lexington Kentucky. Walkable cities are healthy. 

This repository represents part of a GEO409 curriculum developed at the University of Kentucky, [Department of Geography](https://geography.as.uky.edu/).

## Resources

The [data](data) directory contains a ArcGIS File Geodatabase that contains streets with sidewalks, paved off-road pedestrian lanes (aka shared use paths), Census blocks with population counts, annotation layer for street names, and a network analysis layer. 

The [arcgis-assets](arcgis-assets) folder contains `.lyr` Layer files to help with the symbology when adding layers in ArcGIS. A few `.mxd` ArcGIS Map documents use layers from previous mention file geodatabase. ArcGIS toolbox `.tbx` files have Model Builder tools. Two tutorials show in PDF files show how to edit features and calculate population density.


## Calculating sidewalks on streets methodology

Lexington's [2007 Impervious layer](https://data.lexingtonky.gov/dataset/impervious_2007) shows polygons for sidewalks. If a road segment centerline had its center point was within 30 feet of a sidewalk polygon, the segment was assumed to have a sidewalk. 

## Examples
Maps and analysis for Fayette County
* Map of [roads with sidewalks](https://outragegis.com/tiles/fayette/sidewalks/). 
* Analysis of pedsheds using only sidewalks and shared uses paths ([PNG, 6.8 MB](https://github.com/boydx/walkability-analysis/blob/master/example-output/LexingtonWalkabilityAnalysis.png))
* TileMill map ([zoom into Lexington](http://sweb.uky.edu/~blshea1/pedshed/))

