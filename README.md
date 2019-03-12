# Walkability analysis
An exercise at mapping sidewalks and pedsheds in Lexington Kentucky. Walkable cities are healthy.

This repository represents part of a GEO409 curriculum developed at the University of Kentucky, [Department of Geography](https://geography.as.uky.edu/).

## Resources

The [data](data) directory contains a ArcGIS File Geodatabase that contains layers that show streets with sidewalks, paved off-road pedestrian lanes (aka shared use paths) Census blocks with population counts, annotation layer for street names, and a network analysis layer. 

## Calculating sidewalks on streets methodology

Lexington's [2007 Impervious layer](https://data.lexingtonky.gov/dataset/impervious_2007) shows polygons for sidewalks. We calculated for each road segment centerline if its centroid was within 30 feet of a sidewalk polygon. If this was true, the road centerline was assumed to have a sidewalk. The map is [here](https://outragegis.com/tiles/fayette/sidewalks/).

