# ArcGIS API for Python
The ArcGIS API for Python is a Python library for working with maps and geospatial data, powered by web GIS. It provides simple and efficient tools for deep learning, sophisticated vector and raster analysis, geocoding, map making, routing and directions, as well as for organizing and managing a GIS with users, groups and information items. In addition to working with your own data, the library enables access to ready to use maps and curated geographic data from Esri and other authoritative sources. It also integrates well with the scientific Python ecosystem and includes rich support for Pandas, Scikit-Learn, Fast.ai, etc. and Jupyter notebook.

To learn more about the API, visit the product page [here](https://developers.arcgis.com/python/). You can get in touch with the developers of the API and other users like you at the community page [here](https://geonet.esri.com/groups/arcgis-python-api/).

## Raster Processing
The focus of this repository is the raster related functions within the ArcGIS API for Python. Specifically the examples included are from a research paper titled, ["How Do You Define a Tree? Creating a Carbon Sequestration Report for River Ridge Ranch Using Unoccupied Aerial Vehicles"](https://www.academia.edu/79845788/How_Do_You_Define_a_Tree_Creating_a_Carbon_Sequestration_Report_for_River_Ridge_Ranch_Using_Unoccupied_Aerial_Vehicles) by Brandon George, Kane Diaz, and Kevin Bodrogi.

## Abstract of Paper
River Ridge Ranch, a prior cattle ranch for over a century, is now recovering from the intense grazing, and returning to its natural state of being an oak woodland. A study was held at a portion of the ranch, known as Gary's Swath, to determine if key biomass parameters, tree species, height, diameter at breast height, and health could be collected via an unoccupied aerial vehicle, or UAV, to run an accurate carbon sequestration report for the area. An eBee UAV collected nadir and off nadir aerial imagery while in-situ data was gathered using the Collector application for accuracy reporting. After being processed with ArcGIS Pro and Pix4DMapper, the data was processed through iTree software to create an estimate of carbon sequestration for Gary's Swath. Gary's Swath sequestered 13.42 tons ($2.29 thousand/year) of carbon with live oak being the best overall tree species for carbon sequestration. The project was 71 percent accurate, with considerations for the methodology being applied to the whole ranch. Further improvements are recommended for data collection, imagery analysis, image processing, coding applications, regression and statistical analyses and application programming interfaces, or APIs, and all other processes outlined in this methodology. This is in order to increase accuracy of the carbon sequestration report and generate far reaching applications towards other work.

## What's included
This repository contains the following items:
* Jupyter Notebooks created for research and automation of raster processes: Canopy Height Model (CHM), NDVI, NDRE, and Supervised Classification

There are multiple ways of executing these notebooks as listed below:

 - Execute locally on your computer by installing anaconda and the API. See help [here](https://developers.arcgis.com/python/guide/install-and-set-up/#Get-Conda-with-Anaconda-for-Python-Distribution)
 - Execute with ArcGIS Pro. See help [here](https://developers.arcgis.com/python/guide/install-and-set-up/#Get-Conda-with-ArcGIS-Pro)
 - Execute with ArcGIS Hosted Notebooks. See [here](https://www.esri.com/en-us/arcgis/products/arcgis-notebook-server)
 - Execute in a Dockerised environment. See help [here](https://developers.arcgis.com/python/guide/install-and-set-up/#Install-as-a-Docker-image)
 - Execute with Binder. See help [here](https://mybinder.org/)

## Issues
Find a bug or want to request a new feature?  Please let me know by submitting an issue. Thank you!

## Contributing
Anyone and everyone is welcome to contribute.

## Licensing
A copy of the license is available in the repository.

