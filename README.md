# calculate-concentration
Required Data:
EPA air quality csvs (linked below)
Shapefile of California counties (linked below)

This script is designed to take PM2.5 data from the Environmental Protection Agency website along with a California shapefile and create a map showcasing the average concentration calculated from two years.   
The repository contains two python files, update_csv and Calc_Concentration_script.  update_csv's purpose is to take the csv data downloaded from the EPA website (linked below) and 
prepare it to be worked on in Calc_Concentration_script.  When finished, it will create another csv named CA_PM_YEAR, where YEAR is based on the year the csv represents.
Calc_Concentration_script performs the analysis and creates CA_PM_Conc_YEAR1_YEAR2Points (The air quality stations that contain the concentration levels under PM_Concentration) 
and CA_PM_ConcYEAR1_YEAR2 (the county file containing the average concentration level under the field name MEAN).  YEAR1 and YEAR2 represent the years the user can either change based on which csv files they downloaded.

California shapefile link
https://data.ca.gov/dataset/ca-geographic-boundaries

Environmental Protection Agency website link 
https://www.epa.gov/outdoor-air-quality-data/download-daily-data

Pollutant: PM2.5
Year: Any 2 years you wish to study
Geographic Area: California
Monitor Site: All Sites
Get Data (Will download a csv file)
