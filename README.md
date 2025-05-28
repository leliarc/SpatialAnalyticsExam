# Spatial Analytics Exam

This repository contains the code and data for the final exam project in the Spatial Analytics course at Aarhus University. 
This project aims to do a least-cost analysis of the original marathon. The analysis includes a least-cost path analysis based on a digital elevation model (DEM) of Greece, which is used to determine the most efficient route for the Greek messenger allegedly completing the journey from Marathon to Athens. An estimation of metabolic costs is also included. 

## Data acquisition
The data is available in in the GitHub repository in the form of five .tif files in the folder called “elevation data”. In the R script, the five files are merged into 1 DEM covering the desired area of Greece. The data can also be accessed and downloaded through the EarthExplorer website https://earthexplorer.usgs.gov/ 

## Analysis steps
The script follows this rough structure: 
1. Load the necessary libraries and data
2. Preprocessing of the data
3. Creating and using function for calculating statistics for the runs
4. Calculating least-cost paths
5. Visualizing the results
