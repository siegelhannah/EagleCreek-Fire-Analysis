# Remote Sensing Analysis of Vegetation Burning and Regrowth - Eagle Creek Fire

This remote sensing project utilizes supervised classification models and remote sensing techniques (band composites, NDVI change detection) to analyze satellite imagery, assessing vegetation damage and recovery in the context of the Eagle Creek forest fire. Python Scikit-Learn, ArcGIS Pro, QGIS, and Google Earth are used to process and visualize changes over time, delivering ecological insights about the region’s regrowth.


# This repository contains the following files:

## DATA:

- **data/EagleCreekFire.shp:** Study area extent of the Eagle Creek fire; this polygon was used to clip the satellite imagery band layers I downloaded
- **data/randompoints_layer.kml:** Random points generated inside the study area shapefile; used to train the classification models
- **data/2017-2018-changedetection.tif:** NDVI change detection raster 1
- **data/2018-2023-changedetection.tif:** NDVI change detection raster 2

#### In each folder, for 2017, 2018, and 2023:

- **important_used_bands folder:** The specific Landsat 8 bands I used, as well as NDVI, true-color, and custom band composite rasters, *clipped to my study area extent*
- **classification folder:** My trained classification model for each year, with confidence raster & confusion matrix
- **a shapefile for the random points classified for that year**


## DELIVERABLE MAPS:

- **PDFs of all the map figures shown in the written report**
- **finalprojectlayers.qgz:** My final project layers


**The entire written report, with map layouts, is also viewable in the pdf document Eagle_Creek_Project.pdf.**
