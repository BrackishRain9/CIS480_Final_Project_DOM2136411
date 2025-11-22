Maricopa County Housing Analysis
Overview:
  This project aimed to analyze the overall Maricopa county housing market based on publically available information gathered through Zillow and PolicyMap. The project looked at approximately 1000 records within the maricopa county from a Zip code level to a neighborhood level of granularity for median house prices in each of those levels. The project aimed to answer several questions including does population density have an effect on residental home prices and the ability of single income median earners to be able to purchase homes in the area. 
Technologies Used:
  Anaconda navigator
  Jupyter
  Python
  Scikitlearn
  Matplotlib
  RandomForests
  LinearRegression
  PowerBI
  Excel
Reproduction:
  The data set will be the hardest part to reproduce but the steps used to gain the information are listed below:
    1: open https://www.zillow.com/research/data/ and download the Home Values data for 1 bedroom through 5+ bedroom homes and Condos for each City, Neighborhood, and Zip
    2: Combine all files via python to create a singluar data file
    3: Filter all information on the County column to only include Maricopa County
    4: Create new file with filtered information

  Data Cleaning:
    1: Assign all neighborhoods to assoicated Zip code found on zillow
    2: Assign cities to most common Zip for city found on zillow
    3: Drop all columns before 1/30/2020
    4: Drop all rows with information missing

  Model Preparation:
    1: Split data into a test and train set with a 20/80 split
    2: Use Pricing data from 2020, House type, Zip code, and Population Density to predict housing prices
    3: Scale training data to provide better results
    4: Use trained model to predcit and confirm scores based on R2 value
File Structure:
/1Bed contains the Data for the 1 bedroom residences
/2Bed contains the Data for the 2 bedroom residences
/3Bed contains the Data for the 3 bedroom residences
/4Bed contains the Data for the 4 bedroom residences
/5Bed contains the Data for the 5 bedroom residences
/Condo contains the Data for the Condos
/PolicyMapData2025-10-24(1) Contains Policy Map data about Median value homes (Data used as reference not active in file)
/PolicyMapData2025-10-24(2) Contains policy map data about median earner income
/Other Data Contains Income and population density data sets as well as final data set post zip code additions for Indexing
Capstone Programming contains all code for this project
Capstone Report contains the Power BI information for the project
/Reports contains all written reports from this project
  
