# Spatial Analytics Exam

This repository contains the code and data for a spatial analytics project about the original marathon. 

## Data acquisition
The data is avaiable in in the GitHub repository in the form of five .tif files in the folder called “elevation data”. In the R script, the five files are merged into 1 DEM covering the desired area of Greece. The data can also be accessed and downloaded through the EarthExplorer website https://earthexplorer.usgs.gov/ 

## Analysis steps
The script follows this rough structure: 
1. Load the necessary libraries and data
2. Preprocessing of the data
3. Creating and using function for calculating statistics for the runs
4. Calculating least-cost paths
5. Visualizing the results
