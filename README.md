# EDS 240-National Risk Index and Ethnicity Visualization
#### Author : Sofia Rodas

This repository answers:
**How do FEMA National Risk Index scores for counties in California compare to those in other states?**   
**AND**  
**How does climate hazard risk exposure vary across racial / ethnic groups in California?**   



## Data Access:

**FEMA National Risk Index (2023 Release)**: FEMA data is publicly available and can be accessed [here](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025).

**American Community Survey (ACS) Census data (2023 Release)**: Census data is publicly available and can be accessed [here](https://data.census.gov/). The census data can also be directly downloaded in R with an API. The code to do so is in this [quarto document]().

**Hexbin Geospatial file**: Hexbin geojson files can be downloaded [here](https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map).

## File structure:
<img width="365" height="190" alt="Screenshot 2026-02-12 at 6 24 01 PM" src="https://github.com/user-attachments/assets/e97a4123-a4fe-4542-942a-3240df3fa1a3" />


**Note:** Data was added to .gitignore.

## Repository Contents:

-**Quarto document:** [Hexbin graph](https://github.com/sofiiir/eds240-nri-acs-viz/blob/main/hw2/hw2.qmd).  Calculates the percentage of counties in each state that have an NRI score in the "Relatively High" category and a hexplot visualizing the results.  
-**Quarto document:** [Stacked Bar Plot]()  Explores the racial and ethnic break down of each county relative to their NRI categorical scores.  
-**Quarto document:** [Data and graph exploration](https://github.com/sofiiir/eds240-nri-acs-viz/blob/main/exploration.qmd)

### References:

-U.S. Census Bureau, “American Community Survey (ACS),” 2023, <http://api.census.gov/data/2023/acs>, accessed on February 8, 2026.

-Federal Emergency Management Agency (FEMA), National Risk Index Dataset: National Risk Index County_National Risk Index_Rating_Composite - v1.20. Retrieved from [https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025) on January 24, 2025, 12:34 PM EST. This product uses the FEMA National Risk Index dataset API or downloadable datasets but is not endorsed by FEMA. The Federal Government or FEMA cannot vouch for the data or analyses derived from these data after the data have been retrieved from the Agency's website(s).

-Hill, A. us_states_hexgrid. GeoJSON file. [https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map](https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map)
