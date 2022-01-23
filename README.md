# Problem Statement 
The California Cooperative Oceanic Fisheries Investigations (CalCOFI) are a unique partnership of the California Department of Fish & Wildlife, NOAA Fisheries Service and Scripps Institution of Oceanography. The organization was formed in 1949 to study the ecological aspects of the sardine population collapse off California. The CalCOFI data set represents the longest (1949-present) and most complete (more than 50,000 sampling stations) time series of oceanographic and larval fish data in the world. It includes abundance data on the larvae of over 250 species of fish; larval length frequency data and egg abundance data on key commercial species; and oceanographic and plankton data. The physical, chemical, and biological data collected at regular time and space intervals quickly became valuable for documenting climatic cycles in the California Current and a range of biological responses to them. CalCOFI research drew world attention to the biological response to the dramatic Pacific-warming event in 1957-58 and introduced the term “El Niño” into the scientific literature.

Data collected at depths down to 500 m include: temperature, salinity, oxygen, phosphate, silicate, nitrate and nitrite, chlorophyll, transmissometer, PAR, C14 primary productivity, phytoplankton biodiversity, zooplankton biomass, and zooplankton biodiversity. 

The aim is to find whether or not there is a relationship between water salinity & water temperature and if the water temperature can be predicted based on salinity?

## Dataset

The dataset used is the CalCOFI dataset (https://www.kaggle.com/sohier/calcofi/download) from Kaggle. Regression analysis will be used for the given task.

**Target Variable: Water temperature**
<br>
<br>
Water temperature refers to the temperature of the water sample in degree Celsius
<br>
**Mean water temperature:** 10.799677	degree Celsius
<br>
**Max water temperature:** 31.140000 degree Celsius
<br>
**Min water temperature:** 1.440000 degree Celsius


## Model(s) Used

The models used in this task are multiple liner regression and polynomial regression.

**Linear regression :**
<br>
Linear regression is a basic and commonly used type of predictive analysis.  
The overall idea of regression is to examine two things: 
(1) does a set of predictor variables do a good job in predicting an outcome (dependent) variable?  
(2) which variables in particular are significant predictors of the outcome variable, and in what way do they–indicated by the magnitude and sign of the beta estimates–impact the outcome variable?  
These regression estimates are used to explain the relationship between one dependent variable and one or more independent variables.  The simplest form of the regression equation with one dependent and one independent variable is defined by the formula y = c + b*x, where y = estimated dependent variable score, c = constant, b = regression coefficient, and x = score on the independent variable.

**Polynomial regression :**
<br>
Polynomial Regression is a regression algorithm that models the relationship between a dependent(y) and independent variable(x) as nth degree polynomial.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.
