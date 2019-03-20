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

### WeaponUsed_Classification_Process
Contains a description of the process of taking 915 different WeaponsUsed classifications and condensing them down to 24 categories. 
