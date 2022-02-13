# Data-Collection-and-Curation-Assignment

A map visualization above represents the Male and Female percent of the total Latino population living below the poverty level for every county in Texas.

Obtain data from Census Reporter: https://censusreporter.org/data/table/?table=B17001I&geo_ids=04000US48,050|04000US48&primary_geo_id=04000US48#valueType|estimate
Contains Poverty Status in the Past 12 Months by Sex by Age (Hispanic or Latino) for all Texas Counties (2020 Census) 
Table B17001I

libraries needed for jupyterNotebook/jupyterLab: pandas, geopandas, matplotlib

Data: I used the geojson file to download the data to be able to make spatial analysis on this data set since it include the geometry coordinates
Data is can also be obtained through : https://data.world/dv9297/dccddaliavazquezmappingtexaslatinospovertylevels
Data set is also publishesd here: https://data.world/dv9297/datacollectionandcuration-dv9297

Goal: My goal was to create a map that demonstrated the percent of Male/Female Latino/as living below the poverty rate for each county in Texas. 

Process: I used the geojson file to filter out all the columns I wanted. Which only included the adult data columns. I then ensured I updated the total for the male, female and overall total population living below the poverty level.

Once I cleaned the data set I normalized the data set by dividing the total female population living below poverty by the total population living below poverty and then multiplied it by 100 to get the percent. I did this for male and female in a new column. 

Visualization: In order to visualize both population percents I created subplots to see both populations side by side in a Choropleth style map to demonstrate the significant percent diffrences. 

Results:
The Map of Latinas living below poverty demonstrates that there is a high concentration of poverty near the coastal counties of Texas as well as the valley/border counties of Texas. Similiar to the Latinas the male Latino map demonstrates that there is a high concentration of of people living below poverty level in the coastal and border counties of Texas. The only signinficant change here is that the male map has a high rate of poverty in central and western counties of Texas.

Conclusions: 
There has been exponential growth in the Latino population in the last few decades. Seeing higher concentrations of Latinos living below poverty level is not new or surprising since in the past few years the costal counties of Texas have suffered multiple natural disaster and flooding, leaving families in really hard living situations. The same applies for the counties near the valley where major flooding occurs. As for central Texas we see the cost of living rising making it really hard for Latino/as to live above the poverty level. 

Limitations:

I did not include the non-Hispanic groups into the analysis, this analysis was purely a comparison within the Latino population. Therefore this analysis might not be very impactful if you wanted to compare these to other populations. 
