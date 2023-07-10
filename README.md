# Sidewalks Project
The Sidewalks project aims to develop an accessibility score for the sidewalk network in the City of Boston to promote equity, safety, and walkability for all members of the community. By identifying inaccessible sidewalks and potential inequities in accessibility, this project aims to create a more proactive approach to sidewalk maintenance and repair.

# Objectives
Develop an accessibility score for the sidewalk network in the City of Boston
Identify inaccessible corridors in different districts and neighborhoods
Assess routes to access essential services
Develop a proactive sidewalk maintenance strategy based on accessibility scores and prioritization criteria

# Progress

We have made significant progress in our project to identify and address inequities in sidewalk accessibility throughout Boston. 
We began by analyzing four key datasets related to the city's infrastructure - Ramps, Roadway Centerline, Sidewalk Hazards, and Sidewalks - to gain a better understanding of the accessibility and safety for pedestrians and individuals with disabilities. By examining these datasets. we were able to gather insights into the city's accessibility infrastructure, including the locations of ramps, the centerlines of roadways, potential hazards on sidewalks, and the extent and conditions of sidewalks throughout the city.

Additionally, we have analyzed information from Boston's public schools to identify the top 5 schools with the most sidewalks within a 15-minute walking distance. 

Furthermore, we expanded our analysis by examining four additional datasets - Public Works Active Work Zones Data, Climate Ready Social Vulnerability Data, 311 Requests, and Census Demographic Data - to gain a comprehensive view of Boston's infrastructure and demographic landscape. This analysis has helped us identify areas of improvement and develop strategies for addressing key challenges facing the city.


# File Structure
```markdown
├── COLLABORATORS
├── LICENSE
├── README.md
├── spring23-team-1
│   ├── README.md
│   ├── data
│   │   ├── 311.csv
│   │   ├── 311_new.csv
│   │   ├── Boston_Neighborhoods
│   │   ├── Boston_Neighborhoods.geojson
│   │   ├── Colleges_and_Universities.csv
│   │   ├── Hospitals.csv
│   │   ├── JSON_files
│   │   ├── MBTA_Systemwide_GTFS_Bus_Stops_Map.csv
│   │   ├── MBTA_Systemwide_GTFS_T_Stops_Map.csv
│   │   ├── Public_Schools.csv
│   │   ├── Public_Schools.geojson
│   │   ├── Ramp_score.csv
│   │   ├── Ramps_0.csv
│   │   ├── Ramps_0_Updated.csv
│   │   ├── Ramps_0_with_score.csv
│   │   ├── Ramps_Scored_Data_Description.xlsx
│   │   ├── Roadway_Centerline_2.csv
│   │   ├── Sidewalk_Hazards_1.csv
│   │   ├── Sidewalks_3.csv
│   │   ├── census-demographic-housing-data.csv
│   │   ├── climate-ready-social-data.csv
│   │   ├── combined_areas_of_interest.csv
│   │   ├── combined_demographics.csv
│   │   ├── merged_sidewalks_and_hazards.csv
│   │   ├── merged_sidewalks_and_ramps.csv
│   │   ├── preprocessed_sidewalks_hazards.csv
│   │   ├── public-works-active-data.csv
│   │   ├── public-works-data.csv
│   │   ├── ramps_0_with_swk.csv
│   │   ├── shape
│   │   ├── sidewalk_hazards_with_sidewalks.csv
│   │   ├── sidewalks_hazard_score_split.csv
│   │   ├── sidewalks_score.csv
│   │   └── sidewalks_score_main.csv
│   ├── deliverables
│   │   ├── Deliverable-0.pdf
│   │   ├── Deliverable-1-Report.pdf
│   │   ├── Deliverable-2-Report.pdf
│   │   └── Deliverable-3-Report.pdf
│   ├── files
│   │   ├── 311_analysis.ipynb
│   │   ├── 3857
│   │   ├── RampScore.ipynb
│   │   ├── RampScoreAnalysis.ipynb
│   │   ├── RoadwayCenterlineInitAnalysis.ipynb
│   │   ├── SideWalk_Hazard_Analysis.ipynb
│   │   ├── accessibility_score.ipynb
│   │   ├── area_of_importance_analysis.ipynb
│   │   ├── demographics_analysis.ipynb
│   │   ├── initial_analysis.ipynb
│   │   ├── public_works_analysis.ipynb
│   │   ├── ramps_0.ipynb
│   │   ├── ramps_0_score_analysis.ipynb
│   │   ├── routing.ipynb
│   │   ├── sidewalks_3_Analysis.ipynb
│   │   ├── sidewalks_ramps_score.ipynb
│   │   └── sidewalks_score.ipynb
│   ├── graphs
│   │   ├── demographics
│   │   ├── ramps_score
│   │   ├── roadway_centerline
│   │   ├── sidewalks
│   │   ├── sidewalks_hazards
│   │   ├── top_10_bottom_10_accessibility_score_by_location_type
│   │   └── top_10_bottom_10_accessibility_score_by_location_type.html
│   ├── maps
│   │   ├── 311_map.html
│   │   ├── areas_of_importance.html
│   │   ├── areas_of_importance_accessibility_score.html
│   │   ├── children_boston.html
│   │   ├── disability_boston.html
│   │   ├── disability_with_hazards.html
│   │   ├── housing_boston.html
│   │   ├── low_income_boston.html
│   │   ├── medical_boston.html
│   │   ├── older_adults_boston.html
│   │   ├── population_boston.html
│   │   ├── public-works
│   │   ├── ramps_0
│   │   ├── ramps_score
│   │   ├── sidewalks
│   │   └── sidewalks_hazards
│   ├── scrum_report
│   │   ├── Scrum Report 4 - Week of Feb 27th.pdf
│   │   ├── Scrum Report 5 - Week of Mar 13th.pdf
│   │   ├── Scrum Report 6 - Week of Mar 20th.pdf
│   │   ├── scrum_report_1.pdf
│   │   ├── scrum_report_2.pdf
│   │   └── scrum_report_3.pdf
│   └── team-1-info-page

files/ - This directory contains all the python files that are executable.
graphs/ - This directory contains graphs generated by the respective files.
maps/ - This directory contains HTML files (maps) generated by the respective files.
data/ - This directory contains the dataset collected so far.
```

# How to Run
Each analysis has it's own python file.

1. Navigate to the file [analysis] you wish to run.
2. Run every cell.
3. Maps will be saved in the maps/ directory.
4. Graphs will be saved in the graphs/ directory.

# Dependencies
1. Pandas
2. Numpy
3. Matplotlib
4. folium
5. shapely
6. geopandas
7. asyncio

