# vest-nc-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-north-carolina-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

### Raw from source: 

- VEST, North Carolina 2016
    - Accessed, 03/09/2021
    - Source: VEST on the Harvard Dataverse

    - Link to VEST 2016 Datasets: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/NH5S2I&version=56.0
- Election Results for 11/08/2016
    - Accessed, 03/10/2021
    - Source: North Carolina State Board of Elections (NCSBE)

    - Link to Election Data for 11/08/2016:
https://dl.ncsbe.gov/?prefix=ENRS/2016_11_08/
    - Note: The election dataset discussed in this report is titled:
“results_sort_20161108.zip”. To access this file from the main NCSBE download
page (https://dl.ncsbe.gov/ ), select “ENRS/”, then the election “2016_11_08/”,
then “results_sort_20161108.zip”. Last updated by the NCSBE on 02/13/2017.

- Voter Registration for 11/08/2016
    - Accessed, 03/22/2021
    - Source: NCSBE
 

    - Link to Election Data for 11/08/2016:
https://dl.ncsbe.gov/?prefix=ENRS/2016_11_08/
   - Note: The voter registration file discussed in this report is titled:
“voter_stats_20161108.zip”. To access this file from the main NCSBE download
page (https://dl.ncsbe.gov/ ), select “ENRS/”, then the election “2016_11_08/”,
then “voter_stats_20161108.zip”. Last updated by the NCSBE on 02/13/2017.


- Precinct Shapefile for 11/08/2016
    - Accessed, 03/09/2021
    - Source: NCSBE

    
    - Link to state-wide precinct shapefiles:
https://dl.ncsbe.gov/?prefix=PrecinctMaps/
    - Note: The precinct shapefile discussed in this report is titled: “SBE_PRECINCTS_20161004.zip” (It is the most recent file available prior to
the 11/08/2016 election). To access this file from the main NCSBE download
page (https://dl.ncsbe.gov/ ), select “PrecinctMaps/”, then
“SBE_PRECINCTS_20161004.zip”. Last updated by the NCSBE on 10/04/2016.

### File processing:

- `vest-nc-2016-validation.ipynb` - used to process raw files and recreate VEST's work

