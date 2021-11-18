# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Gilbert Harlim Putra
- Student ID: 1006990
- Due Date: Friday 16th of August 11:59:00 am (AEST).
- Report Link: https://www.overleaf.com/read/zwnszcbqpjkm
- Report Word Count: LaTEX (2041) and Turnitin (2529) 
# Dependencies
- Language: Python 3.9.5 & Apache Spark 3.1.2
- Packages / Libraries: pandas, numpy, pyspark, sklearn, statsmodels, folium, matplotlib, seaborn

# Datasets
- NYC TLC : https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- Taxi Zones : https://data.cityofnewyork.us/Transportation/NYC-Taxi-Zones/d3c5-ddgc
- Global Hourly Climate data (EXTERNAL) : https://www.ncei.noaa.gov/data/global-hourly/archive/csv/

# Directory
- `raw_data`: Contains all the raw data files. 
- `preprocessed_data`: Contains all the preprocessed data files.
- `plots`: All figures are located here.
- `code`: A folder to store essential codes for the project. (Run the notebook in the order noted below)
    1. __*Data Extraction*__ : Download all essentials dataset.
    2. __*Data Preprocessing Step 1*__ : Initial Cleaning of TLC dataset
    3. __*Data Preprocessing GHC*__ : Preprocessing GHC dataset
    4. __*Data Preprocessing Step 2*__ : merging TLC and GHC and also creating a sample data.
    5. __*Data Analysis*__ : Preliminary Analysis Notebook
    6. __*Statistical Modelling*__ : Statistical Modelling Notebook
- `deprecated`: "old code" "obsolete code" "sad code :("

# Project Planning
1. Extract :
    1. 2018 Yellow Taxi dataset 
    2. 2019 Yellow Taxi dataset
    3. Global Hourly Climate Data 2018 
    4. Global Hourly Climate Data 2019
4. Clean 2018 and 2019 Yellow Taxi dataset
5. Merge with GHC 2018 and 2019 dataset, create a sample for both years
6. Analyze and Visualize 2018 merged dataset.
7. Train 2018 model (preferrably 80/20 split from the sample)
8. Predict the sample of 2019 YTX dataset.
9. Analyze the model.
10. Do the report!
11. DONE <3

# Other
PLAN CAREFULLY BROTHER, DON'T JUST GO BACK AND FORTH MULTIPLE TIMES. IT IS EXHAUSTING, PLEASE REMIND ME! DOING THIS MAKES ME AGE BY 5 YEARS
