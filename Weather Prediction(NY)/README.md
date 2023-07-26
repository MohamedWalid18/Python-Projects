# About The Data 
This Data is from National oceanic and atmospheric adminstration (NOAA) https://www.ncdc.noaa.gov/cdo-web/search , which provides scientific stewardship, products, and services for geophysical data from the Sun to the Earth and Earth’s sea floor and solid earth environment, including Earth observations from space 

Our Data covers the Duration from 1970 to 2022 inculding several predictors such as maximum temprature(TMAX) , minimum temprature(TMIN) & more.

# Objective
To predict The maximum temprature in the future based on the historical data.

# Steps and Procedure
### Preprocessing 
- NULL percentage of each col was calculated then We Dropped cols with NULL precentage greater than( > ) 5%
- Filled in missings with the previous NON_NULL value
- Correcting Data Types for our variables

### Model Used
- Analyzing the correlations among predictors, there was a siginficant association between most of them
- Choosing Ridge Regression with Parameter 0.1
- Excluding qualitative variables from the model
- Used backtest process to train & test the model

# Evaluation
- Mean error was almost 5 using mean absolute error metric
- Having added more predictiors the mean error decreased to 4 
