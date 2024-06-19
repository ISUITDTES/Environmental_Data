# <p align=center> Environmental and Epidemiological modeling data 


This repository provides the supplementation for the paper **Co-Benefit Environmental and Health Impact Assessment of Carbon Border Adjustments** conducted by *Huynh T. T. Tran,  Anh Phuong Ngo, 
 Konstantinos Oikonomou,  and Hieu T. Nguyen*.

After installing the COBRA application, the users will find the data stored in the "path_to_COBRA\COBRA\data\cobra.db" file. Using DB Browser (SQLite), we extract the S-R matrix for the base year 2016 and save it as a CSV file.

For the data in the S-R matrix, we sort the S-R matrix and organize it at two levels: county-by-county and state-by-state. The county-level matrix will help you understand local pollutant transfers, while the state-level matrix is useful for visualizations.

For the state-level S-R matrix, we calculate the average transfer of pollutants from all counties in the Western Electricity Coordinating Council (WECC) areas to each county within the state. This will help show the correlation of air quality between states within the WECC areas. Note: we ignore the pollutant transfer from states outside of WECC as it is out of the scope of the research.

The terms "typeindx," "sourceindx," and "destindx" in the S-R matrix file can be found in the data dictionary folder.

The emissions folder contains the baseline emissions data for pollutants for the years 2016, 2023, and 2028 scenarios. This data helps in comparing and analyzing how pollutant levels are projected to change over time.
 
