

# Sidewalks 

**Goal** 

The goal of this project is to create accessibility scores for sidewalks in Boston and identify areas that need improvement. We also aim to find the best routes for people to walk to public facilities.

**Background**

Currently, residents need to call to report sidewalk issues or hazards, which may not be effective in identifying areas that need improvement. By introducing accessibility scores, we can determine the areas that are not receiving proper treatment of their sidewalks.

**Data Analysis**

We have done preliminary analyses on the data and are currently working on doing a more in depth analysis using the newly provided ramp scores, and sidewalk locations. We have plotted the data to a real map and we can have direct visions of them to find our research directions.

**Result**

We have analyzed all of the initial datasets. As for the new ones we have decided to focus more on the ramps data set with its new accessibility score and the sidewalks dataset to determine accessibility scores for entire sidewalks. We aim to make use of all the elements to decide whether a sidewalk is in good conditions. 

**DataSets**: 

The following datasets were used in this project:

- Ramps_new.json
- Sidewalks.json
- Hospitals.csv
- Schools.csv
- and so on

**Maps**: 

We show most of the result we get in map, it can be found in folder data. Map  will show you the sidewalks on a map and allow you to view each sidewalks ID by hovering over it and also see each sidewalks score by clicking on it.

## **HOW TO GET SIDEWALK SCORES**

#### Source

You will need to download the `Ramps_new.json` and the `Sidewalks.json` files.

#### Code

Download the `scores.ipynb` file and keep `Ramps_new.json` and `Sidewalks.json` under the same directory as `scores.ipynb`. In this way, when reading the necessary source file, it can succeed. If you want to make any changes to the directory, you can modify the code below to adjust the structure to meet your needs:

```python
# Load sidewalks file as geopandas dataframe
sidewalks = gpd.read_file('Sidewalks_without_scores.json')
ramps_gdf = gpd.read_file('Ramps New.json')
sidewalks_gdf = gpd.read_file('Sidewalks.json')
```



#### Installation Instructions

##### Requirements

Add dependencies to run all the code we build, using following command.

```shell
pip install -r requirement.txt
```

The required Python packages are:

- pandas
- json
- folium
- pyproj
- geopandas
- shapely
- scipy

##### Troubleshooting

When installing geopandas you may need to install **gdal** as well, however when in install it you may face the problem of below.

```error
lacking mircosoft visual c++2014
```

When installing gdal, you may encounter an error related to missing Microsoft Visual C++ 2014. If this happens, you can download the appropriate .whl file for your machine from https://www.lfd.uci.edu/~gohlke/pythonlibs/ and install it by running the .whl file instead.

#### Add Users

To add yourself to the repository, please open a Pull Request modifying the `COLLABORATORS` file and adding your GitHub username on a new line.

All Pull Requests must follow the Pull Request Template, with a title formatted like so: `[Project Name]: <Descriptive Title>`