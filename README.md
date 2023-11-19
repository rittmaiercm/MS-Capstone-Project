# MS-Capstone-Project

## Project Scope
- Assessing how COVID-19 influenced how far people were willing to drive to visit a park
- Focused on Lakeshore Park (Sequoyah Hills area) and Victor Ashe Park (Pleasant Ridge Area)

## Main Takeaways
- Lakeshore Park saw the distance to the park influencing the number of visitors but they have limited infrastructure that allows people to walk to the park within even a 5 minute area
- Victor Ashe Park did not see distance being a major influence on the number of visitors and accounted for very little statistical significance compared to Lakeshore Park; this can be contributed to the infrastructure surrounding Victor Ashe Park - there are many sidewalks allowing people to walk to the park within a 10 or so minute area

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
