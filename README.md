# calculate-concentration
Environmental Protection Agency website link 
https://www.epa.gov/outdoor-air-quality-data/download-daily-data

This repository allows a user to take California PM2.5 air quality data from the Environmental Protection Agency website and create a map showcasing the average concentration calculated from two years.
This repository contains two python files.  One is called update_csv, the other Calc_Concentration_script.  update_csv's purpose is to take the csv data downloaded from the EPA website (linked above) and 
prepare it to be worked on in Calc_Concentration_script.  When finished, it will create another csv named CA_PM_YEAR, where YEAR is based on the year the csv represents
update_csv can create multiple csvs at once depending on how many csvs the user has within its data folder.

Calc_Concentration_script performs the bulk of the processing and expects the files created by update_csv.  
