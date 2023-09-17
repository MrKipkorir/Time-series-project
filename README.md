# Time-Series-Zillow-House-Prediction


### Table of contents 
- [Project goal](#project-goal)
- [Business Understanding](#business-understanding)
- [Data preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluations)

---

# 1. Business Understanding
### Project goal
The zillow  Dataset contains a wealth of information about the RegionName, City , Metro and various other features of houses in the United States of America . This project will disect how AR, MA, ARMA, ARIMA, and SARIMA models in Python  help predict house prices. IN doing this  the Horizon Real Estate Agency can render constructive advices to homeowners of when they can buy or sell their houses and by what amount.This project considers several  factors that should be looked into when performing this task.

### Overview
Real estate is a lucrative business in any economy due to various factors including the rate of population increase in most countries. Over the last decade, the housing market in the United States has seen every end of the housing spectrum. Real estate market trends peaked more than 10 years ago during the Great Recession. For the most of this year, competition propelled what appeared to be the hottest housing market prices in the industry's history. Buyers were forced to compete with many offers on each home, tipping the scales heavily in favor of sellers. Due to a supply and demand imbalance, homeowners were given an edge. It should be remembered, however, that the approaching prospect of a recession, along with the greatest inflation rate recorded in the US housing market in over four decades, has compelled the Federal Reserve to take extreme action. To battle inflation and slow the economy, the Fed has implemented a number of rate rises, the most significant of which would more than quadruple mortgage rates. 
 
### Business Problem 

Real Estate can be a very risky business but can be lucrative when the risks are understood. The risks can be bad locations, the unpredictable nature of the market et cetera.  Horizon Limited is looking to invest in real estate in the United States and need us to identify the locations that are the best to invest in and forecast the nature of the market. 
------

# 2. Data Understanding
### Overview
Data is sourced from the [Zillow website]  The data used in this project is sampled from the real estate market of the United States. The data contains the median house prices through 22 years, i.e., 1996-2018,  and the regions where the houses are located. 

### Data Description
This data contains 272 columns and 14,723 rows. It has the following columns and descriptions;

`RegionName` - 	Names of the Regions (Zipcodes)
  
`City` - names for the regions
  
`State` -	Names of the states
  
`Metro` -	Names of metropolitan areas
  
`County Name` -	Names of counties
  
`Size Rank` -	Rank of Zipcodes by urbanization
  
`Date Columns` - (265 Columns)	Median house prices across the years
  
------
# 3. Data Preparation
Data preparation entailed:
* Cleaning Data
* Checking Duplicates
* Filling Missing Values
    
------
# 4. Modeling

I  built a time series models using different featuers in the dataset to predict five best locations to invest in based on their return of investment (ROI).
The models include;
* Auto Regressive model(AR)
* Moving Average model(MA)
* ARMA model
* ARIMA model
* SARIMA model

-------
# 5. Evaluation 
The AIC and BIC of the various models, improved as I moved from one modle to the next. My best model was the SARIMA after tuning the parameters, came up with the lowest AIC and Mean Absolute Percentage Error. Given that SARIMA is the best model, seasonality patterns are just as significant when projecting property values as past values.
-------

# 6. Conclusion

* There are several discrepancies within the housing investment sector. Investors would rather invest in some cities than others, which is evident from the varying number of properties in the different cities.
* The top three cities with the highest median house prices are Atherton (California), Palm Beach(Florida), and Snowmass Village (Colorado).
* The cities with the highest ROI in 22 years are New York, Georgia state and Hawaii.
* Houses in New York have the highest home values, followed by California.
* The prices of houses also differ concerning the city ranks. Homes in highly-ranked cities have high median prices.
* Other factors, such as location also dictate changes in the price of house prices. For instance, houses in the coastal regions have higher median prices.
* Using our model, we can also deduce that the growth of home value is bound to slow down considerably in the coming years.

---

# 7. Recommmendations
I advise the Horizon Real Estate Company;
* The company should focus on locations with great beaches and outdoor activities since houses in these locations fetch highest prices as this is seen from cities in California and Florida.
* Invest in the cities, New York and California, which has the highest Return On Investment. 
* Sell at a discounted price to increase sales over the next few years due to the slowing down of real estate price in the foreseeable future. 

https://docs.google.com/presentation/d/1nSwleedCzip4vFeTLU1RsfEHSVrQhHu4TLw34Y08s7E/edit?usp=sharing
---
 
