# Rasterio
Python2.7 --> Some scripts for remote sensing applications using RAsterio instead of GDAL





## 0_to_NAN.ipynb
This script reads all images in a specific folder and replaces all 0's (black border) with Nodata (nan's).


## Mosaic_with_rasterio_merge.ipynb
This script take multiple images (all tifs in a specific folder) and creates a mosaic.


## Reprojecting.ipynb
This Script shows how to reproject satellite data (as batch process or single images) using only the epsg code for the target coordinate system
