# pdv-nc
Partner data validation for North Carolina, from VEST 2020. 

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-north-carolina-precinct-boundaries-and-election-results-shapefile/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source

### Accessible files: 
- VEST NC 20 data file
  - Accessed 10/11/21, Source: VEST
  - https://dataverse.harvard.edu/file.xhtml?fileId=4863162&version=21.0
- VEST NC 20 documentation file
  - Accessed: 10/11/21, Source: VEST
  - https://dataverse.harvard.edu/file.xhtml?fileId=5206372&version=21.0
- NC Unsorted Precinct-Level Election Results
  - Accessed: 10/11/21, Source: ID Secretary of State
  - https://s3.amazonaws.com/dl.ncsbe.gov/ENRS/2020_11_03/results_pct_20201103.zip
  - Note: Used for the counties listed by VEST in their documentation.
- NC Sorted Precinct-Level Election Results
  - Accessed: 10/11/21, Source: ID Secretary of State
  - https://dl.ncsbe.gov/?prefix=ENRS/2020_11_03/results_precinct_sort/
  - Note: Used for the counties listed by VEST in their documentation.
- NC Voting Precincts “20201018” Shapefile
  - Accessed: 10/11/21, Source: North Carolina State Board of Elections
  - https://dl.ncsbe.gov/?prefix=PrecinctMaps/
  - Note: This is the main shapefile VEST uses.
- NC Voting Precincts “20190827” Shapefile
  - Accessed: 10/18/21, Source: North Carolina State Board of Elections
  - https://dl.ncsbe.gov/?prefix=PrecinctMaps/
  - Note: VEST uses this file for a handful of missing precincts.
