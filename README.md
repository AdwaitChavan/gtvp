# Global Temperature vs Precipitation

Learn more about the developer here: https://www.linkedin.com/in/adwaitchavan/

**Global Temperature vs Precipitation** is a Data Science project with the goal to learn Machine Learning & Data Science via Python. The project uses data on global temperature and precipitation collected from 85794 locations globally. Train-test split & Exploratory Data Analysis (EDA) were performed on the cleaned data. Utilized sklearn, numpy & pandas libraries. Multivariate Linear Regression model was implemented for prediction of annual temperature in this supervised learning. Stats Models API was used for OLS Regression Results in order to analyze & conclude relationship between the two entities.  

The features of the model are each of the months of January, February, March, April, May, June, July, August, September, October, November, and December. The reason for choosing these features is because the trends in annual precipitation vary vastly with respect to monthly temperature depending on which month of the year it is. 
A small practical example of this could be that these days we experience more fluctuations in precipitation in some months, when all of the months have almost the same changes in temperature due to global warming.

## Data
The data that we have consists of Monthly Air Temperatures (in oC), and Monthly Precipitation (in mm) respectively from January 1900 to December 2014 based on latitudes and longitudes of locations. Thus, our dataset contains Air Temperature (in oC) and Precipitation (in mm) for every month of these 115 years.
This dataset contains 2 files containing Monthly Air Temperatures and Precipitation, each from January 1900 to December 2014 in csv format.
Both of these datasets have a size of 85794 rows x 1382 columns. Lastly, this also means that we have data tracked for 85794 locations based on their latitudes and longitudes. We collected our data form after a really extensive research from the website https://climatedataguide.ucar.edu/climate-data/global-land-precipitation-and-temperature-willmott-matsuura-university-delaware which contains Terrestrial Temperature and Precipitation Data collected by the University of Delaware. 

## Interesting Observations from EDA
#### Plotting the mean annual precipitation of all years, along with mean annual precipitation in 1900, and mean annual precipitation (in mm) in 2014


<p align="center">![precippppp image](https://user-images.githubusercontent.com/57969397/123930935-cd047100-d955-11eb-843b-26d77caf80b9.png)</p>

We see that the annual precipitation in 2014 has greatly reduced in the first half of the year, which is generally hotter, compared to the second half of the year. Also, from the months of August to December in 2014, we again see that the rainfall has indeed decreased compared to mean rainfall and rainfall in 1900.

