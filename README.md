# The Data-Driven Guide to Crime in Milwaukee 
mke_crime is a repository for a Medium article [here](https://medium.com/p/b6a373f898e9/edit). 

### About
Utilizing the publicly available [WIBR Crime Data](https://data.milwaukee.gov/dataset/wibr) from [The City of Milwaukee Open Data Portal](https://data.milwaukee.gov/), 
I capture and evaluate 666,790 crime incidents considered Group A Offenses that occurred from March 2005 through December 2018.
While the data file itself exceeds the upload limits of Github, documentation for downloading the data is available in the codebook.

### codebook
The codebook provides documentation of the data analysis and allows for reproducibility.
Analyses are contained within three sections of the code and appear in sequential order: 

1) Time-based Visualization 
2) Weapon-based analyses
3) Geospatial analyses and clustering.

Initially, exploratory geospatial maps were creating utilizing ggmaps and the ggplot system are included in the code. 
Specific subsets of code were downloaded as .csv files and then uploaded to [kepler.gl](https://kepler.gl/) where the final maps images were produced.
Links to interactive versions of the maps, included the data used to create the figure may be found in the figure captions within the Medium article.
### mke_data_dictionary 
Contains a description of the variables in the data set. Also available [here](https://data.milwaukee.gov/dataset/wibr/resource/87843297-a6fa-46d4-ba5d-cb342fb2d3bb).

### WeaponUsed_Classification_Process
Contains a description of the process of taking 915 different WeaponsUsed classifications and condensing them down to 24 categories. 


### map data 2018
The dataset was uploaded to kepler.gl for map creation of the hexagonal denisty mappings. This data set contains the variables crime, latitude, and longitude. You can use this data to recreate the mapping from the Medium article. 

### mke_clust_2018 & clust_table_edited 
These tables contain the data that was uploaded to kepler.gl for map creation of the cluster data. mke_clust_2018 contains the latitude, longitude, and cluster labels, while clust_table_edited contains the icon assignments and mappings for the approximate cluster centers. You can use this data to recreate the mapping from the Medium article. 
