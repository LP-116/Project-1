# Project 1: House Pricing in Australia

## Group members: Leanne Porter, Mathew Johnson, Sreemanth Gurram & John Mikhail

---

### Project Details
“What does house pricing look like in Australia? How has it changed over the years and does the household income growth match these changes?”

We set out to identify if the highest priced states in Australia also have the highest wage. 
Our hypothesis was that the highest priced states should also have the highest wage.
We then looked further into Victoria and tried to get the same answers based on suburbs.

We came up with the following questions to ask in order to draw our conclusions:

* What does house pricing look like in Australia?
* How different is pricing between city and regional?
* How has the pricing changed over the years?
* What does the future look like?
* Is there a correlation between house pricing in Australia and the average household income?

We then decided to take a deeper look into Victoria and asked:
* What does house pricing look like in Victoria?
* How different is pricing between city and regional?
* How has the pricing changed over the years?
* What type of growth has there been?
* Is there a correlation between house pricing in VIC suburbs and the average household income?

----

### Data Analysis
The main source of our data came from government websites - the ABS website and the Australia Government Data website.

The data required quite a bit of clean up and merging in order to get the data required for the analysis.
To complete the analysis we used a number of different actions including:

* Merging and exporting csv files
* Removing and renaming columns
* Converting the original data to numerical data
* Sorting the data
* Completing calculations on particular columns and adding new columns to the dataset
* Displaying graphs
* Completing quartile and outlier calculations
* Removing missing data
* Using Google maps API's to retrieve data and display heatmaps.

For further detail regarding our analysis, please refer to the jupter notebooks in the main branch of the repository.
Notes on these notebooks are also below in the files section.

---
### Observations

Please refer to the Analysis summary document in the main branch for a summary of our findings.

---
### Files
There are 7 files in the main branch of this repository that contain our analysis and data cleanup.
Details on these files are below:

* Top 5 and Bottom 5 Suburbs in Victoria.ipynb  (completed by Sree)
<br />This notebook completes some analysis on Victorian suburbs and identifies the top and bottom 5 suburbs in Victoria based on price change between different periods of time. Graphs and the data cleanup process are included.
  
* Extracting state wage details.ipynb (completed by Leanne)
<br />This notebook shows how the missing years for the state wage analysis were extracted.
  
* Extracting suburb wage details.ipynb (completed by Leanne)
<br />This notebook shows how the wage details were extracted for the suburb income analysis.

* Final suburb analysis.ipynb (completed by Leanne)
<br />This notebook is the bulk of the suburb analysis. The heatmaps are included in this notebook and it also shows the data cleanup process.

* State price predictions.ipynb (completed by John)
<br />This notebook shows how the house price predictions were calculated for each state. Graphs and the data cleanup process are included.
  
* Suburb salary analysis.ipynb (completed by Leanne)
<br />This notebook shows how the suburb salary analysis was completed. Graphs and the data cleanup process are included.

* House Price Forecast.ipynb (completed by Mathew)
<br />This notebook shows how the house price forecast analysis was completed. Graphs and the data cleanup process are included.

* House Price Analysis.ipynb (completed by Mathew)
<br />This notebook shows how the state and regional house price analysis was completed. Graphs and the data cleanup process are included.

* Reformatting VIC.ipynb (completed by Mathew)
<br />This notebook shows the process of reformatting VIC data.

* Regression Analysis.ipynb (completed by Mathew)
  <br />This notebook shows how the regression analysis was completed. Graphs and the data cleanup process are included.
  
* Images folder - this folder contains images of all graphs generated in the analysis 
* Data files - This folder contains all csv files used/exported in our analysis.
* Analysis Presentation - A powerpoint version of our presentation. (completed by all)
* Analysis summary - A summary of our findings. (written contributions by all but document prepared and finessed by Mathew)
 
 ---
### Data sources

Data sources:

State house price analysis:
https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/residential-property-price-indexes-eight-capital-cities/latest-release#data-download


State income analysis:
https://www.abs.gov.au/statistics/labour/earnings-and-work-hours/personal-income-australia/latest-release#data-download
https://www.abs.gov.au/statistics/labour/earnings-and-work-hours/average-weekly-earnings-australia/latest-release#data-download

Suburb house price analysis:
https://discover.data.vic.gov.au/dataset/victorian-property-sales-report-median-house-by-suburb

Suburb income analysis:
https://data.gov.au/data/dataset/taxation-statistics-postcode-data/resource/b713d037-d9f5-49e5-a492-502cd7b3a15a

---
### Further notes
Please note you will need a Goodle maps API to run some of the files.
To create a Google maps API key please navigate to https://developers.google.com/maps/documentation/embed/get-api-key
Create a new file to store your API key. The google maps key needs to be stored as "g_key = "ENTER CODE HERE". Without the API key, the code will not run.




