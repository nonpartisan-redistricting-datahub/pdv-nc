# pdv-nc
Partner Data Validation for North Carolina. Data Partner: MGGG

[Final Report](https://docs.google.com/document/d/129My9DDLlN8FJMoIkpMk8v-dj8gCM1b7KRp9Td8-v0k/edit#heading=h.zdykup2sf3ru)

**Raw from source:**
- North Carolina VTD Shapefile w/ Election Results:
  - Online: https://www.ncleg.gov/Redistricting/BaseData2016 (“Geographic Data” -> “Assignment Layers (counties, VTDs, blocks)”
  - AWS: `R2016_Assignment_Layers.gdb`
- Census Block to VTD Keys
  - Online: https://www.ncleg.gov/Redistricting/BaseData2016 ("Numeric Data" -> "Datasets" -> "Block Level Keys")
  - AWS: `Block_Level_GeoKeys.tab`
- 2012 Election Data
  - Online: https://er.ncsbe.gov/downloads.html (Election: 11/06/2012 -> “Available Election-related Files” -> “results_sort_20121106.zip”)
  - AWS: `results_sort_20121106.txt`
- 2016 Election Data
  - Online: https://er.ncsbe.gov/downloads.html (Election: 11/08/2016 -> “Available Election-related Files” -> “results_sort_20161108.zip”)
  - AWS: `results_sort_20161108.txt`
- 2011 NC Congressional District Plan
  - Online: https://www.ncleg.gov/Redistricting (“Congressional District Plans” -> “Enacted 2011” -> “Shapefile”)
  - AWS: `2011_shp/Rucho_Lewis_Congress_3.shp`
- 2016 NC Congressional District Plan
  - Online: https://www.ncleg.gov/Redistricting (“Congressional District Plans” -> “Enacted 2016” -> “Shapefile”)
  - AWS: `2016_shp/2016_Contingent_Congressional_Plan_Corrected.shp`
- MGGG NC File
  - Online: https://github.com/mggg-states/NC-shapefiles
  - AWS: `NC_VTD/NC_VTD.shp`

**File Processing:**
- MGGG File: https://github.com/mggg-states/NC-shapefiles  
- Processing and Validation Steps: `MGGG_NC_replication.ipynb`  
- Note / Methodology: Comments on `MGGG_NC_replication.ipynb`
