# WetlandData

Geospatial data are retrieved from USGS data releases associated with [Mushet et al. (2022, USGS Professional Paper 1874)](https://doi.org/10.3133/pp1874).

Climate data are retrieved from various sources. NLDAS2 (NASA) is downloaded using the HyRiver python sofware stack [https://github.com/hyriver/hyriver.github.io](https://github.com/hyriver/hyriver.github.io). GRIDMET (UC Merced), PRISM (Oregon State), and DAYMET (ORNL) are downloaded using the Google Earth Engine python API. The processed data sets represent the zonal average of grid cells that fall within a bounding box `(-99.108739,47.093980,-99.088818,47.106746)` surrounding the study area.
