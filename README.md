## Data hub for Cottonwood Lake Study Area wetlands

Geospatial and hydrybiogeochemical data are retrieved from USGS data releases associated with [Mushet et al. (2022, USGS Professional Paper 1874)](https://doi.org/10.3133/pp1874).

Climate data are retrieved from various sources. NLDAS2 (NASA, ~14-km grid) is downloaded using the [HyRiver python sofware stack](https://github.com/hyriver/hyriver.github.io). GRIDMET (UC Merced, 4-km grid), PRISM (Oregon State, 4-km grid), and DAYMET (ORNL, 1-km grid) are downloaded using the [Google Earth Engine python API](https://earthengine.google.com/). The processed data sets represent the zonal average of grid cells that fall within a bounding box `(-99.108739,47.093980,-99.088818,47.106746)` surrounding the study area.
