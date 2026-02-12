# EDS 240-National Risk Index and Ethnicity Visualization
#### Author : Sofia Rodas

This repository answers:
**How do FEMA National Risk Index scores for counties in California compare to those in other states?**   
**AND**
**How does climate hazard risk exposure vary across racial / ethnic groups in California?** 


To answer this question, this repository calculates the number of counties in each state that have an NRI score in the "Relatively High" category and plots them. 

## Data Access:

**FEMA National Risk Index (2025 Release)**: FEMA data is publicly available and can be accessed [here](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025). 

**Hexbin Geospatial file**: Hexbin geojson files can be downloaded [here](https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map).

## File structure:
<img width="424" height="115" alt="Screenshot 2026-01-28 at 11 54 58 PM" src="https://github.com/user-attachments/assets/0b77e244-0cdf-401f-aa33-c8f9bb8115a5" />

**Note:** Data was added to .gitignore.

## Repository Contents:

-**Quarto document:** [Hexbin graph](https://github.com/sofiiir/eds240-nri-acs-viz/blob/main/HW2.qmd)  
-**Quarto document:** [Data and graph exploration](https://github.com/sofiiir/eds240-nri-acs-viz/blob/main/exploration.qmd)

### References:

-Federal Emergency Management Agency (FEMA), National Risk Index Dataset: National Risk Index County_National Risk Index_Rating_Composite - v1.20. Retrieved from [https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025) on January 24, 2025, 12:34 PM EST. This product uses the FEMA National Risk Index dataset API or downloadable datasets but is not endorsed by FEMA. The Federal Government or FEMA cannot vouch for the data or analyses derived from these data after the data have been retrieved from the Agency's website(s).

-Hill, A. us_states_hexgrid. GeoJSON file. [https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map](https://team.carto.com/u/andrew/tables/andrew.us_states_hexgrid/public/map)
