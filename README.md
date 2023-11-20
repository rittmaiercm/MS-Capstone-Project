# MS-Capstone-Project

## Project Scope
- Assessing how COVID-19 influenced how far people were willing to drive to visit a park
- Focused on Lakeshore Park (Sequoyah Hills area) and Victor Ashe Park (Pleasant Ridge Area)

## Conclusions for Each Park
- Lakeshore Park
     - The distance that people traveled to get to the park was the top factor affecting visitor numbers
     - This was expected since there is limited infrastructure that people could use to walk to the park
- Victor Ashe Park
     -  Distance did not heavily influence visitor numbers
     -  This could be attributed to the well-developed infrastructure surrounding the park within a 10 minute walking radius such as sidewalks and walking trails leading to different parts of the park

## Data
- Geodatabase: capstone_gdb.gdb
     - Files ending in '_spatialjoin' are the end results used for the OLS Regression Models
- CBGS Counts by Season (excel file)
     - Raw datasets obtained from the SafeGraph database for each park by each season
- Demographics TN (shapefile)
     - Shapefile that contains the demographic information for each census tract
     - Use the GEOID column as the unique identifier to join to the unique identifier for each tract within the SafeGraph dataset
- Knox County Outline (shapefile)  
     - Knox and nearby counties boundary outline
- Knoxville Park Boundaries (shapefile)
    - Used to get the centroid for each park
- Park Distance
    - Files were used to show the distance from the park centroid to each census tract centroid
- Transformed Datasets
    - Datasets projected into the spatial projection - NAD_1983_2011_StatePlane_Tennessee_FIPS_4100

## Capstone Project Outputs
- Departmental Forms
- OLS Figures and Maps
- Graphs and Chart Images
- Near Distance Files
- OLS Map Outputs 
- OLS Regression Plots 
- OLS Tables
