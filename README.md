# calculate-concentration
Required Data:
EPA air quality csvs (linked below)
Digital Elevation Model

This script is designed to take air pollution data from the Environmental Protection Agency website and create a map showcasing the average concentration calculated from two years.  The repository 
contains two python files, update_csv and Calc_Concentration_script.  update_csv's purpose is to take the csv data downloaded from the EPA website (linked below) and 
prepare it to be worked on in Calc_Concentration_script.  When finished, it will create another csv named CA_PM_YEAR, where YEAR is based on the year the csv represents.
Calc_Concentration_script performs the analysis.

Environmental Protection Agency website link 
https://www.epa.gov/outdoor-air-quality-data/download-daily-data
Pollutant: PM2.5
Year: Any 2 years you wish to study
Geographic Area: California
Monitor Site: All Sites
Get Data (Will download a csv file)
