# Comparison of weather data from different weather monitoring stations (namely, Promice, S6 and B&B from Greenland)

Version of this script: v7 (last update: 05/12/2020)

Author: Nuno Canha

# Goal of the script: 
This script aims to combine 3 different weather datasets (with the parameters: timestamp, temperature, relative humidity, wind speed and wind direction) and compare them using plots and spearman correlations.

This script uses datasets of three weather stations located at Greenland (S6, KAN_M and B&B). 
The input files should be "csv" type, with hourly values (pre-treatment should be done if needed). In this page, you can find example of 3 csv files of weather databases (KAN_M, S6 and B6B, all for the year of 2017).
The output of this script will be 17 figures, with temporal series of the weather parameters, statistical summary (mean and standard deviation) and spearman correlations.
The updated script is entitled: Comparison of WD_v7_Hour analysis.ipynb 

Updates of current version:
Timestamps of the input files were corrected to match
