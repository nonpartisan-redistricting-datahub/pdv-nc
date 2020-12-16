# pdv-nc2

	1. Aggregate Demographic Data from Census Block Level to VTD
	2. Assign Districts from the 2011 enacted congressional district plans, 2016 enacted congressional district plans, and the judge's plan to VTDs
	

	raw-from-source
	

1. VTD Shapefile NC: 
	
A. MGGG stated they received VTD shapefile from the North Carolina General Assembly's 			2016 Redistricting Reference Data
B. NCLEG > Redistricting Archives> 2016 Redistricting Reference Data>Geographic Data> "The geographic data in the General Assembly's redistricting system is based on the 2010 Tiger/Line Shapefiles provided by the US Census Bureau"
C. Following B, we can get the 2010 VTD shapefiles for North Carolina at [https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-	file.html]
D. Difficulty in getting shapefile from that website, used this link instead, from the the US Census [https://catalog.data.gov/dataset/tiger-line-shapefile-2012-2010-state-north-carolina-2010-census-voting-district-state-based-vtd]
	

2. Block-Level shapefile: [https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-north-carolina-current-block-group-state-based]
	

3. Historical Election Data: [https://www.ncsbe.gov/results-data/election-results/historical-election-results-data]
	
	
A. MGGG stated they received election data from the North Carolina General Assembly's 2016 Redistricting Reference Data
B. NCLEG>Redistricting Archives>2016 Redistricting Reference Data>Numeric Data>Datasets>by Voting Tabulation District

i) ELection Data 2008-2012 contest results are disaggregated using a commercially-available utility. VTD-level counts were broken out based on the ratio of block-level census voting age population to VTD-level voting age population. Since results are fractional, they were truncated down to the nearest whole vote. The remainders of all blocks within a VTD were then added to the highest population block within that VTD.

ii) This is the exact dataset that MGGG used, however, this file does not have the 2012 presidential election and 2016 elections. We had to get them from a seperate file

iii) From the Data Processing Notes at NCLEG's 2016 Redistricting Database, [https://www.ncleg.gov/Files/GIS/Base_Data/2016/Numeric/Data_Processing_Notes_2016.pdf], NCLEG obtained election results from the North Carolina State Board of Elections at the VTD-level. VTDs are equivalent to the voter precincts as they existed on January 1st, 2008. 

iv) County-wide votes found in the VTD-level data files falling under categories such as 'absentee','transfer','provisional' were excluded due to the homogenizing effect on the VTD-level data. Statewide candidate vote totals are marginally less than those reported in the official contest results due to this reason.
v) Election results were matched directly to the 2010 census VTD geography
	
	The excluded 2012 and 2016 election files are found at the NC State Board of Elections > Historical Election Results Data

	2016 Election Data (results_pct):11/6/2016 file
	2012 Election Data (results_pct): 11/6/2012 file
	
	

	Processing Notes for 2016 Election Data: [https://www.ncleg.gov/Files/GIS/Base_Data/2016/Numeric/Data_Processing_Notes_2016.pdf]
	

	2016 Election Data reported by MGGG does not match up with what is reported by State Board of Election.
	  Validation done in two ways. 1. By checking total sum by party of State Board of Elections dataset 
	                               2. Comparing MGGG reports with the total sum by party as reported on State Board of Election Dataset
	                               3. Sum by party of State Board of Elections dataset and the reported sum on website matches up
	                               4. Emailed State Board of Election on 10.09.2020 inquiring if the General Elections results for 2016 has                                   ever been updated. They confirmed it has not been updated since 2/13/2017
				       
	
	4. Enacted District Plans
	a. 2011:
	b. 2016:
	c. judge:
	  


