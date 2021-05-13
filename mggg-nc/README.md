# mggg-nc

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/mggg-north-carolina-vtds-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

### **Raw from source:**
- North Carolina VTD Shapefile w/ Election Results:
  - Online: https://www.ncleg.gov/Redistricting/BaseData2016 (“Geographic Data” -> “Assignment Layers (counties, VTDs, blocks))”
  - AWS: `R2016_Assignment_Layers.gdb` (available upon request)
- Census Block to VTD Keys
  - Online: https://www.ncleg.gov/Redistricting/BaseData2016 ("Numeric Data" -> "Datasets" -> "Block Level Keys")
  - AWS: `Block_Level_GeoKeys.tab` (available upon request)
- 2012 Election Data
  - Online: https://er.ncsbe.gov/downloads.html (Election: 11/06/2012 -> “Available Election-related Files” -> “results_sort_20121106.zip”)
  - AWS: `results_sort_20121106.txt` (available upon request)
- 2016 Election Data
  - Online: https://er.ncsbe.gov/downloads.html (Election: 11/08/2016 -> “Available Election-related Files” -> “results_sort_20161108.zip”)
  - AWS: `results_sort_20161108.txt` (available upon request)
- 2011 NC Congressional District Plan
  - Online: https://www.ncleg.gov/Redistricting (“Congressional District Plans” -> “Enacted 2011” -> “Shapefile”)
  - AWS: `2011_shp/Rucho_Lewis_Congress_3.shp` (available upon request)
- 2016 NC Congressional District Plan
  - Online: https://www.ncleg.gov/Redistricting (“Congressional District Plans” -> “Enacted 2016” -> “Shapefile”)
  - AWS: `2016_shp/2016_Contingent_Congressional_Plan_Corrected.shp` (available upon request)
- MGGG NC File
  - Online: https://github.com/mggg-states/NC-shapefiles
  - AWS: `NC_VTD/NC_VTD.shp` (available upon request)

**File Processing:**
- MGGG File: https://github.com/mggg-states/NC-shapefiles  
- Processing and Validation Steps: `mggg-nc.ipynb`  
- Note / Methodology: Comments on `mggg-nc.ipynb`
