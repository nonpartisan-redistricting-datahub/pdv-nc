# pdv-nc2

	1. Aggregate Demographic Data from Census Block Level to VTD
	2. Assign Districts from the 2011 enacted congressional district plans, 2016 enacted congressional district plans, and the judge's plan to VTDs
	

	raw-from-source
	

	1. VTD Shapefile NC: [https://catalog.data.gov/dataset/tiger-line-shapefile-2012-2010-state-north-carolina-2010-census-voting-district-state-based-vtd]
	

	2. Block-Level shapefil: [https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-north-carolina-current-block-group-state-based]
	

	3. Historical Election Data: [https://www.ncsbe.gov/results-data/election-results/historical-election-results-data]
	

	2016 Election Data:11/6/2016 file
	2012 Election Data: 11/6/2012 file
	

	4. Precinct (Not VTD) shapefiles: [https://www.ncsbe.gov/results-data/voting-mapsredistricting] , didn't use them but would like to store this link
	

	

	

	Processing Notes for 2016 Election Data: [https://www.ncleg.gov/Files/GIS/Base_Data/2016/Numeric/Data_Processing_Notes_2016.pdf]
	

	2016 Election Data reported by MGGG does not match up with what is reported by State Board of Election.
	  Validation done in two ways. 1. By checking total sum by party of State Board of Elections dataset 
	                               2. Comparing MGGG reports with the total sum by party as reported on State Board of Election Dataset
	                               3. Sum by party of State Board of Elections dataset and the reported sum on website matches up
	                               4. Emailed State Board of Election on 10.09.2020 inquiring if the General Elections results for 2016 has                                   ever been updated. They confirmed it has not been updated since 2/13/2017
	  


