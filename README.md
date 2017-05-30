# CartoCamp_Workshops

This repository has contents for the 2 workshops that I conducted at Carto, Brooklyn in April and May 2017. For both workshops, Jupyter Notebooks were used as a means of instruction. Details of the two workshops are as follows:

## 28th April 2017 - Introduction to OSMnx for Routing

The purpose of this workshop is to understand OSMnx amd to use it for routing specific use cases. The jupyter [notebook](https://github.com/ManushiM/CartoCamp_Workshops/blob/master/Workshop1_April2017/CartoCamp_OSMnx.ipynb) for this Workshop touches upon the following topics:

* Introduction to OSMnx
* Extracting boundary shapefiles
* Extracting street networks
* Basic spatial analysis
* Finding shortest distance from origin to destination
* Detecting walkable distance within 5,10,15 mins from a location
* Extracting data for external use
* Visualizing results internaly and externaly

Outputs generated while executing the scripts in the notebook have been saved in the 'osmnx_outputFiles' folder.

In order to run these scripts on your own computer, clone this repository and install the necessary packages (Networkx, Geopandas, Matplotlib, Rtree, OSMnx, Pandas, Numpy, Descartes, Folium).

Another segment of this same workshop involved a Carto employee instructing on ways to extract routing data using Google Maps API. Contents for that segment can be found [here](https://github.com/CartoCamp/workshops/tree/master/2017-04-28-carto-camp-routing)

## 26th May 2017 - Introduction to D3

This workshop focuses on understanding D3 and its components, and using Citibike data extracted in the [previous workshop](https://github.com/CartoCamp/workshops/tree/master/2017-04-28-carto-camp-routing) to build a map animation. The jupyter [notebook](https://github.com/ManushiM/CartoCamp_Workshops/blob/master/Workshop2_May2017/CartoCamp_D3.ipynb) for this Workshop touches upon the following topics:

* What is D3?
* Understanding Scales, Axes, Data
* Understanding Data Binding, Path and Transformations
* Going through code to build these [charts](https://manushim.github.io/CartoCamp_Workshops/Workshop2_May2017/code/staticCharts)
* Going through code to build this bike route D3 [animation](https://manushim.github.io/CartoCamp_Workshops/Workshop2_May2017/code/citibike_animation) based on trip id.

The html code for the charts and the animation are in the 'code' folder. And data used to build the bike route animation is in the 'data' folder.

In order to run these scripts on your own computer, clone this repository and follow the 'NOTE' at the bottom of the [tutorial notebook](https://github.com/ManushiM/CartoCamp_Workshops/blob/master/Workshop2_May2017/CartoCamp_D3.ipynb).
