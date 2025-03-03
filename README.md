<h1 align="center"> Exploring Marine Protected Area Data </h1>
<h3> EDS220_Fall2022 Final Project </h3>

<img align="right" src="santa_barbara_coastline.jpg" width="300">


The purpose of this repository is to provide a walk-through of how to utilize NOAA's marine protected area (MPA) dataset located at the [MPA Inventory website](https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/). There are many packages that can potentially be used to visualize this dataset, but we chose 'folium'. Folium is a python library built off a JavaScript Library called Leaflet. Both of these packages are free, open-source libraries that allow the user to create maps and visualize data in a similar way to google maps. This dataset is useful in visualizing MPAs, and understanding how MPAs interact with marine processes. This can include data to examine the effect of MPAs on factors such as fishing, IUCN marine species risk status, species distributions, and ecosystem resiliency in light of ocean acidification and changes in sea surface temperature. In this notebook we visualize MPA data in conjuction with sea otter range data from the California Department of Fish and Wildlife, as well as inaturalist data on purple sea urchins. Ultimately, we hope that this notebook will be a useful educational tool for those looking to explore this dataset. 
# Included in the Notebook:
- Notebook Purpose
- Description of the Data
- Data Input and Output (I/O)
- Metadata Display and Basic Visualization
- Use Case Examples
- References

# Data Citation:
- Department of Commerce, National Oceanic and Atmospheric, Administration, Office Of National Marine Sanctuaries (, National Marine Protected, and Areas Center. 2020. “NOAA’s Marine Protected Areas Inventory - 2020 - IUCN MPAs.” https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/.
- “Sea Otter Range - CWHR M164 [Ds1946].” n.d. Accessed November 29, 2022. https://data-cdfw.opendata.arcgis.com/datasets/CDFW::sea-otter-range-cwhr-m164-ds1946/explore?location=34.902570,-120.447472,7.00.
- “Strongylocentrotus Purpuratus (Stimpson, 1857).” n.d. Accessed November 29, 2022. https://www.gbif.org/species/2278852.




# Folder Structures:
If working outside a binder environment, the raw data read into the notebook is housed under a shared folder in a UCSB Master of Environmental Data Science server called “Taylor”. Access to the data from the server is limited. The data can be downloaded [here](https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/). The repository can be run in a binder environment without data download. 

# Libraries Used:
- Geopandas
- Pandas
- Folium
- Matplotlib
- OS
- GeoJson
- CSV
- Json
- Shapely
- Rtree

# Authors:
- Colleen McCamy, Master of Environmental Data Science Student, (colleenmccamy@bren.ucsb.edu)
- Atahualpa Gomez, Master of Environmental Data Science Student, (atahualpa@ucsb.edu)
- Jared Petry, Master of Environmental Data Science Student, (jaredpetry@ucsb.edu)
- Adelaide Robinson, Master of Environmental Data Science Student, (adelaide_robinson@ucsb.edu)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/adelaiderobinson/Coastal-Coders_EDS220_FinalProject/HEAD)

