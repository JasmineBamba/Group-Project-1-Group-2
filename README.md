# Group-Project-1
First Group Project: Group 2

- Jasmine Bamba
- Caroline Bordin
- Nikita Gahoi

# Datasets:
- http://nfdp.ccfm.org/en/data/fires.php
- https://cwfis.cfs.nrcan.gc.ca/ha/nfdb

# Objective
* To explore whether there is a correlation between CO2 emissions and the frequency of wildfires in Canada.
* To track and visualize the historical number of wildfires in Canada over the years.
* To investigate the potential correlation between wildfire frequency and the months of the year.
* To assess the impact of deforestation on fire spread patterns compared to natural forested areas.
* To plot the causes of wildfire
* To analyze the cause of wildfires in different provinces. 

# Team questions:
- Caroline:
          * Impact of Deforestation on Fire Behavior: Analyze fire spread patterns in deforested areas compared to natural forested areas. 
- Nikita:
          * Calculate the no. of wildfires in each month
          * Plot the geolocations of all the Jurisdictions based on the number of fires
          * Map the trend if any to understand if there are a few months where the frequency of the wildfire is more Correlation
          * Analyze the correlation between the frequency of wildfires and CO2 emissions
          * Calculate the number of wildfires for each Jurisdiction based on the fire causes
- Jasmine:
          * Calculate the number of wildfires for each cause class. Is there a correlation between the frequency of wildfires and the different cause classes?
          * Map the trend, if any, to understand if certain cause classes are more prevalent in contributing to wildfires.

# Data Cleaning
For this project, extensive data cleaning was performed to ensure the accuracy and reliability of the dataset used for analysis. The following data-cleaning tasks were applied to the raw data:

- Handling Missing Values: NaN values were replaced with 0
- Removing Duplicates: The columns in the datasets were in French and English, with the same column title. Renaming the columns and dropping the duplicate columns 
  (French) in the dataset 
- Removing Irrelevant Information: Unnecessary columns or data points that did not contribute to the analysis were removed to streamline the dataset
- For the fire dataset, the values for the year 2021 were dropped, as most of the values in the dataset were estimated values
- The data for Deforestation and CO2 emissions were for the years 2000-2020, therefore the data from the years 1990-1999 was dropped from the wildfire data and the   data files were merged for further analysis

# Observation and analysis:
## Causes of wildfire:
          * Major causes of wildfires in Canada are Human Activities (53.6 %) and Lightning (42.3%)
          * The major cause of wildfire in British Columbia and Nova Scotia is lightning
          * On the contrary, In Alberta, New Brunswick and Quebec, the main cause of wildfire is Human Activities          
## Geolocation of wildfires based on provinces:         
          * Most of the Wildfires are accumulated in the south of Canada, this could be because:
                -The Higher Population density in these areas leads to increased cases of wildfire due to human activities
                -The temperature is more favorable and is warmer towards the South of Canada, leading to an increased number of wildfires
                -The land covered in the forest could be another possible reason for a larger number of wildfires in these jurisdictions
## Total number of wildfires for each Jurisdiction: 
          * In the past 31 years, British Columbia has experienced the maximum number of forest fires, followed by Alberta and Ontario
          * The Jurisdiction with the least number of Wildfires are Prince Edward Island, Newfoundland and Labrador, and Yukon
## Total number of wildfires caused across months:
          * The months with the highest temperatures in Canada (July and August) witnessed the maximum number of wildfires, followed by June and May
          * Excessively large number of wildfires occured in British Columbia during the month of July and August
          * As from the previous data on Causes, British Columbia probably has a very high number of wildfires due to lightning and Temperature during the months               of July and August
## Impact of Deforestation on Fire Behavior:
          * Wildfires and forestry are the main factors of deforestation representing more than 98% of the causes.
          * A positive correlation was observed between the deforestation area and the area burnt by wildfires 
## Correlation between CO2 emission and number of fires:
          * There was no correlation observed between the wildfire and Total Co2 Emissions (mg) during the years
          * Therefore, an analysis was performed to look for the correlation between the CO2 emissions due to Wildfire and total number of wildfires each year:
                    -A very weak correlation of 0.23 was observed 
