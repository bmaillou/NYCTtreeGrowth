# NYCTtreeGrowth
Analysis of NYC Tree Census data to determine growth rates.   This site will provide the data and python scripts used in the analysis to calculate tree growth rates.  

## Scripts
1. Combine NYC raw data into one Database:  This script takes the NYC 2005 and NYC 2015 Tree census data and combines them into one data base aligned by postal code, address, species.  It then exports the combined file to excel.
    1. Input files
        1. 2005_Street_Tree_Census.csv
        2. 2015_Street_Tree_Census_-_Tree_Data.csv   
    1. Output Files
        1. PaperVersionUncleaned_05_15_combined.xlsx
    1. Output figures
        1. None
    1. Output Data
        1. None                   
1. Clean_all_growth_data: This takes the combined database and then cleans the data. It does some basic descriptive statistics and exports the cleaned database for further analysis.
    1. Input files
        1. PaperVersionUncleaned_05_15_combined.xlsx
        1. 2015_Street_Tree_Census_-_Tree_Data.csv   
    1. Output Files
        1. Cleaned_NYC_Growth.xlsx
    1. Output Figures
        1. Multiple but none used in Paper
    1. Output Data
        1. Summary of basic tree growth used in results
        1. Data for Table 2                  
1. Figure1_and_2_Growth_Plots:  This uses the cleaned and uncleaned NYC growth databases for ground truthing and temrporal validation and presenting the firts figures.
    1. Input files
        1. PaperVersionUncleaned_05_15_combined.xlsx
        1. 2015_Street_Tree_Census_-_Tree_Data.csv   
    1. Output Files
        1. Cleaned_NYC_Growth.xlsx
    1. Output Figures
        1. Multiple but none used in Paper
    1. Output Data
        1. Summary of basic tree growth used in results
        2. Data for Table 2  
7. ARCgis scripts are performed offline to add more data to the NYC growth database for comparisons
8. Forest_Plot_statistics: Uses the cleaned NYC growth database with the additional data to do the statistical analyses
9. Maps: Creates the maps


I am not sure how I made that image!


![image](https://github.com/bmaillou/NYCTtreeGrowth/assets/8991003/696bf23b-021a-4805-acf7-a9556b115bbd)


