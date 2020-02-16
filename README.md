# LIDAR-Height-Extractor
Implementation of an algorithm using Python to remotely extract building heights by combining LIDAR (Light Detection and Ranging) datasets and building shapefiles.

*Steps*
1. Read Las
2. Converting LAS file To Pandas Dataframe
3. Spatial merge LIDAR and shapefile by geometry columns
4. Calculate median height of building by grouping by building ID
5. Create Buffer From The Building Edges
6. Spatial Merge Lidar And Buffer Line By Geometry Columns
7. Calculate Ground Level Of LIDAR Z Points In Border By Grouping By Building Id
8. Create Dataframe Of Building ID And Building Height
9. Merge Into Final Detailed Table
10. CSV Extraction
11. SHP Extraction

Datasets ad visualizations cannot be displayed as they were proprietary.
