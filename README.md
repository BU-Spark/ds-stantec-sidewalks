 ```markdown
 
#Sidewalks Project
The Sidewalks project aims to develop an accessibility score for the sidewalk network in the City of Boston to promote equity, safety, and walkability for all members of the community. By identifying inaccessible sidewalks and potential inequities in accessibility, this project aims to create a more proactive approach to sidewalk maintenance and repair.

#Objectives
Develop an accessibility score for the sidewalk network in the City of Boston
Identify inaccessible corridors in different districts and neighborhoods
Assess routes to access essential services
Develop a proactive sidewalk maintenance strategy based on accessibility scores and prioritization criteria

#Progress

We have made significant progress in our project to identify and address inequities in sidewalk accessibility throughout Boston. 
We began by analyzing four key datasets related to the city's infrastructure - Ramps, Roadway Centerline, Sidewalk Hazards, and Sidewalks - to gain a better understanding of the accessibility and safety for pedestrians and individuals with disabilities. By examining these datasets. we were able to gather insights into the city's accessibility infrastructure, including the locations of ramps, the centerlines of roadways, potential hazards on sidewalks, and the extent and conditions of sidewalks throughout the city.

Additionally, we have analyzed information from Boston's public schools to identify the top 5 schools with the most sidewalks within a 15-minute walking distance. 

Furthermore, we expanded our analysis by examining four additional datasets - Public Works Active Work Zones Data, Climate Ready Social Vulnerability Data, 311 Requests, and Census Demographic Data - to gain a comprehensive view of Boston's infrastructure and demographic landscape. This analysis has helped us identify areas of improvement and develop strategies for addressing key challenges facing the city.


#File Structure
├── README.md
├── data
│   ├── 311.csv
│   ├── 311_new.csv
│   ├── JSON_files
│   │   ├── RampsNew
│   │   ├── SidewalkHazards
│   │   └── Sidewalks
│   ├── Public_Schools.csv
│   ├── Public_Schools.geojson
│   ├── Ramp_score.csv
│   ├── Ramps_0.csv
│   ├── Ramps_0_Updated.csv
│   ├── Ramps_0_with_score.csv
│   ├── Ramps_Scored_Data_Description.xlsx
│   ├── Roadway_Centerline_2.csv
│   ├── Sidewalk_Hazards_1.csv
│   ├── Sidewalks_3.csv
│   ├── census-demographic-housing-data.csv
│   ├── climate-ready-social-data.csv
│   ├── merged_sidewalks_and_hazards.csv
│   ├── preprocessed_sidewalks_hazards.csv
│   ├── public-works-active-data.csv
│   ├── public-works-data.csv
│   ├── ramps_0_with_swk.csv
│   ├── shape
│   │   ├── Ramps.cpg
│   │   ├── Ramps.prj
│   │   ├── Ramps.sbn
│   │   ├── Ramps.sbx
│   │   ├── Ramps.shp
│   │   ├── Ramps.shp.xml
│   │   ├── Ramps.shx
│   │   ├── Roadway_Centerline.cpg
│   │   ├── Roadway_Centerline.dbf
│   │   ├── Roadway_Centerline.prj
│   │   ├── Roadway_Centerline.sbn
│   │   ├── Roadway_Centerline.sbx
│   │   ├── Roadway_Centerline.shp
│   │   ├── Roadway_Centerline.shp.xml
│   │   ├── Roadway_Centerline.shx
│   │   ├── Sidewalk_Hazards.cpg
│   │   ├── Sidewalk_Hazards.dbf
│   │   ├── Sidewalk_Hazards.prj
│   │   ├── Sidewalk_Hazards.sbn
│   │   ├── Sidewalk_Hazards.sbx
│   │   ├── Sidewalk_Hazards.shp
│   │   ├── Sidewalk_Hazards.shx
│   │   ├── Sidewalks.cpg
│   │   ├── Sidewalks.dbf
│   │   ├── Sidewalks.prj
│   │   ├── Sidewalks.sbn
│   │   ├── Sidewalks.sbx
│   │   ├── Sidewalks.shp
│   │   ├── Sidewalks.shp.xml
│   │   └── Sidewalks.shx
│   └── sidewalk_hazards_with_sidewalks.csv
├── deliverables
│   ├── Deliverable-0.pdf
│   ├── Deliverable-1-Report.pdf
│   └── Deliverable-2-Report.pdf
├── files
│   ├── 311_analysis.ipynb
│   ├── 3857
│   ├── RampScore.ipynb
│   ├── RampScoreAnalysis.ipynb
│   ├── RoadwayCenterlineInitAnalysis.ipynb
│   ├── SideWalk_Hazard_Analysis.ipynb
│   ├── demographics_analysis.ipynb
│   ├── initial_analysis.ipynb
│   ├── public_works_analysis.ipynb
│   ├── ramps_0.ipynb
│   ├── ramps_0_score_analysis.ipynb
│   └── sidewalks_3_Analysis.ipynb
├── graphs
│   ├── demographics
│   │   └── demographics-analysis.pdf
│   ├── ramps_score
│   │   └── RampScore.pdf
│   ├── roadway_centerline
│   │   ├── number_of_roads_per_council.pdf
│   │   ├── number_of_roads_per_district.pdf
│   │   ├── number_of_roads_per_function.pdf
│   │   └── number_of_roads_per_jurisdiction.pdf
│   ├── sidewalks
│   │   ├── average_sidewalk_Area_per_district.pdf
│   │   ├── average_sidewalk_width_per_district.pdf
│   │   ├── number_of_sidewalks_per_district.pdf
│   │   └── number_of_sidwalks_15min_school.pdf
│   └── sidewalks_hazards
│       ├── HazardCountinNeighbourhood.pdf
│       ├── HazardTypes.pdf
│       ├── HazardTypesCountinNeigbourhood_H.pdf
│       └── HazardTypesCountinNeigbourhood_V.pdf
├── maps
│   ├── 311_map.html
│   ├── public-works
│   │   └── redzones.html
│   ├── ramps_0
│   │   ├── excellent_location.html
│   │   ├── fair_location.html
│   │   ├── poor_location.html
│   │   └── ramps_conditions.html
│   ├── ramps_score
│   │   ├── ada_not_compliant.html
│   │   ├── combined_ramp_conditions_regions.html
│   │   └── low_ramp_score.html
│   ├── sidewalks
│   │   ├── Sidewalks.html
│   │   ├── Sidewalks_with_hazards.html
│   │   ├── bad_combination_ramps_hazards_sidewalks.html
│   │   ├── ramps_with_sidewalks.html
│   │   ├── ramps_with_sidewalks_and_hazards.html
│   │   └── temp.html
│   └── sidewalks_hazards
│       ├── Fixed pinch point <36” sidewalk width.html
│       ├── Trip hazards due to tree roots.html
│       ├── Trip hazards not due to tree roots.html
│       └── hazard_locator.html
├── scrum_report
│   ├── Scrum Report 4 - Week of Feb 27th.pdf
│   ├── Scrum Report 5 - Week of Mar 13th.pdf
│   ├── Scrum Report 6 - Week of Mar 20th.pdf
│   ├── scrum_report_1.pdf
│   ├── scrum_report_2.pdf
│   └── scrum_report_3.pdf
└── team-1-info-page

files/ - This directory contains all the python files that are executable.
graphs/ - This directory contains graphs generated by the respective files.
maps/ - This directory contains HTML files (maps) generated by the respective files.
data/ - This directory contains the dataset collected so far.


#How to Run
Each analysis has it's own python file.

1. Navigate to the file [analysis] you wish to run.
2. Run every cell.
3. Maps will be saved in the maps/ directory.
4. Graphs will be saved in the graphs/ directory.

#Dependencies
1. Pandas
2. Numpy
3. Matplotlib
4. folium
5. shapely
6. geopandas
7. asyncio


