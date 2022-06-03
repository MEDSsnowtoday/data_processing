# Data Processing

The notebooks contained within this repository create the stacked geotiff files of snow cover percent and albedo that were used to create the file visualized in the [MEDS Snow Today Shiny application](https://shiny.snow.ucsb.edu/snow_today_shiny_app/). The notebook [annual_tiff_stack_function](https://github.com/MEDSsnowtoday/data_processing/blob/main/annual_tiff_stack_function.ipynb) was used to create raster stacks for each water year that include coordinate projection information. The output rasters include 365/366 layers, one for each day in the water year. A water year runs from October 01 to September 30.

The notebook [functions_for_means_and_anomalies](https://github.com/MEDSsnowtoday/data_processing/blob/09dfffb756a51a6686bf623b1720730349d87e0d/functions_for_means_and_anomalies.ipynb) was used to create the raster files (stacked geotiffs) aggregated to monthly and annual timeframes. This notebook calculated monthly and annual averages and anomalies for snow cover percent and albedo.

# Installation

Required packages and python version:

|            |            |                |
| ---------- | -----------| ---------------|
| python 3.8 |  gdal      |  numpy         | 
| rasterio   |  rioxarray |  xarray.       |


