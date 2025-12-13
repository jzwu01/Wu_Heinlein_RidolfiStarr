# Wu_Heinlein_RidolfiStarr Fall 2025 EDE Final Project
Fall 2025 EDE Final Project: Trend Analysis of Water Quality Data in Biscayne Bay: Impacts of Summer Fertilizer Ordinance


## Summary

The repository contains data downloaded from the Florida Statewide Ecosystem Assessment of Coastal and Aquatic Resources (SEACAR) Data Discovery platform, specifically from the city of Miami Beach Water Monitoring program page that provides data points on various water quality monitoring parameters. Trends in pre- and post-fertilizer ordinance implementation in various parameters (total phosphorus, total nitrogen, dissolved oxygen, and pH) are analyzed to assess whether there are significant changes following the ordinance implementation.


## Investigators

Joy Wu, Dash Ridolfi-Starr, Jordan Heinlein

## Keywords

Water Quality, Fertilizer, Nutrients, Fertilizer Ordinance, Biscayne Bay, Phosphorous, Nitrogen, Dissolved Oxygen, pH, Miami Beach, Miami-Dade


## Database Information

The dataset is obtained from Florida Statewide Ecosystem Assessment of Coastal and Aquatic Resources (SEACAR) Data Discovery platform, City of Miami Beach Water Monitoring program page. No other outside data is used for analyses. We did not generate new data, but rather worked to wrangle the existing dataset that we obtained. We access the data in November, 2025.  


## Folder structure, file formats, and naming conventions 

Our repository contains three folders. The “Raw_Data” folder contains the single TXT dataset used in our analysis. “Processed_Data” contains data wrangled as CSV files for different steps in our analysis. The “Code” folder contains our full project code as an Rmd file.  

In file names, “WQ” refers to water quality. The intervals by which averages were taken are also indicated in file names (“monthly,” “yearly,” etc.).  

## Metadata

| Column Name        | Description                                     | Class     | Units |
| ------------------ | ----------------------------------------------- | --------- | ----- |
| Date               | YYYY-MM                                         | Date      | NA    |
| Month              | MM                                              | Factor    | NA    |
| Mean_Phosphorous   | Mean total phosphorous                          | Number    | mg/L  |
| Mean_Total_N       | Mean total nitrogen                             | Number    | mg/L  |
| Mean_Dissolved_02  | Mean dissolved oxygen                           | Number    | mg/L  |
| Mean_pH            | Mean pH                                         | Number    | NA    |
| Year               | YYYY                                            | Factor    | NA    |
| Inter_Phosphorous  | Interpolated phosphorous                        | Number    | mg/L  |
| Inter_pH           | Interpolated pH                                 | Number    | NA    |
| Inter_Dissolved_02 | Interpolated dissolved oxygen                   | Number    | mg/L  |
| Interp_Total_N     | Interpolated total nitrogen                     | Number    | mg/L  |
| Group              | Pre vs post fertilized ordinance effective date | character | NA    |

## Scripts and code

Final code used in this project is saved in the “Code” folder as Final_Project_Code.Rmd 
