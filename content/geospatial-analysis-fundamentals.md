Title: Spatial Analysis Fundamentals
Date: 2010-12-03 10:20
Modified: 2010-12-05 19:30
Category: GIS
Tags: 
Slug: spatial-analysis-fundamentals
Authors: Riley Albiston
Summary: Short version for index and feeds

## What is Geospatial Analysis


## Geospatial Analysis vs GIS



## Spatial Data

Spatial data describes any data which contains information about location. The data will usually be stored as coordinates and/or topology. There are two main types of data format used in spatial analysis. 

**Vector**

Vector data is comprised of three data types:

* Points - discrete data points representing a point of interest. Generally stored as a X and Y coordinate system such as latitude and longtitude.
* Lines - represent linear features such as roads and rivers. They are stored as order sets of points. 
* Polygons - represent a boundry area such as a lake, country boarder etc. Polygons are 'closed' features make of a line that starts and ends at the same point. 

**Shapefiles**

[Shapefile Wiki](https://en.wikipedia.org/wiki/Shapefile)

Shapefiles (.shp) are a geospatial vector data format developed by Esri. Shapefiles can contain all vector data formats (points, lines, and polygons). While the format was developed and is regulated by Esri (ArcGIS) it can be used with other platforms such a python scripts, PostGIS and QGIS. It is important to note that shapefiles are in truth a collection of files which at minimum include:

* .shp — shape format
* .shx — shape index format
* .dbf — attribute format

The file set may also contain many other file types.

**Raster**


## Map Projections - Coordinate Reference System

https://spatialreference.org/

https://en.wikipedia.org/wiki/Spatial_reference_system

https://docs.qgis.org/2.18/en/docs/gentle_gis_introduction/coordinate_reference_systems.html


# Geospatial Software and Programming

## Proprietary Software:

**ArcGIS**

Esri's ArcGIS suite of software products is considered the industry standard for geospatial software. It is used globally by all levels of government and academic institutions. 

## Open Source:

**Python**

Python has many modules for analysing and visualising geospatial data. 

**PostGIS Database**

**QGIS**

