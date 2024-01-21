# NYCTtreeGrowth
Analysis of NYC Tree Census data to determine growth rates.   This site will provide the data and python scripts used in the analysis to calculate tree growth rates. Below I list each script and the data sets used.  The ARCgis methods to add data not in the NYC tree census is not included.   

## Python Notebooks/Scripts
1. 1-Combine NYC raw data into one Database:  This script takes the NYC 2005 and NYC 2015 Tree census data and combines them into one data base aligned by postal code, address, species.  It then exports the combined file to excel.
    1. Input files
        1. 2005_Street_Tree_Census.csv
        2. 2015_Street_Tree_Census_-_Tree_Data.csv   
    1. Output Files
        1. PaperVersionUncleaned_05_15_combined.xlsx
    1. Output figures
        1. None
    1. Output Data
        1. None                   
1. 2-Clean_all_growth_data: This takes the combined database and then cleans the data. It does some basic descriptive statistics and exports the cleaned database for further analysis.
    1. Input files
        1. PaperVersionUncleaned_05_15_combined.xlsx  
    1. Output Files
        1. Cleaned_NYC_Growth.xlsx
    1. Output Figures
        1. Multiple but none used in Paper
    1. Output Data
        1. Summary of basic tree growth used in results
        1. Data for Table 2                  
1. 3-Figure1_and_2_Growth_Plots:  This uses the cleaned and uncleaned NYC growth databases for ground truthing and temrporal validation and presenting the firts figures.
    1. Input files
        1. PaperVersionUncleaned_05_15_combined.xlsx (FIX THIS)
        1. Cleaned_NYC_Growth.xlsx
        1. NYC Trees_V2 - latest.xlsx. (Ground Truthed data)
        1. TemporalValidationData.xlsx
    1. Output Files
        1. None
    1. Output Figures
        1. Figure 1
        2. Figure 2
    1. Output Data
        1. Summary of ground truthed data
        1. Summary of Temporal Validation data  
1. ARCgis scripts are performed offline to add more data to the NYC growth database for comparisons
    1. Input files
        1. Cleaned_NYC_Growth.xlsx
    1. Output Files
        1. tree_census_join_20210613.xlsx
    1. Output Figures
        1. None
    1. Output Data
        1. None
1. 5-Forest_Plot_statistics: Uses the cleaned NYC growth database with the additional data to do the statistical analyses. It outputs the fitted data for the maps.
    1. Input files
        1. tree_census_join_20210613.xlsx
    1. Output Files
        1. fitted_growth_rates.xlsx
    1. Output Figures
        1. Figure 4
        2. Figure 5
        3. Figure 6
    1. Output Data
        1. Summary Statistics
1. 6-for-paper-Take-NYC-growth-Data-Make-maps-ACS.ipynb: Creates the maps
    1. Input files
        1. fitted_growth_rates.xlsx
    1. Output Files
        1. none
    1. Output Figures
        1. Figure 3
        2. Figure 7
        3. Figure 8
    1. Output Data
        1. none

## Paper Cover Page 


![image](https://github.com/bmaillou/NYCTtreeGrowth/assets/8991003/696bf23b-021a-4805-acf7-a9556b115bbd)


