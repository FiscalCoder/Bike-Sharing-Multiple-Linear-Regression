# LinearRegression_Assignment
> A US bike-sharing provider 'BoomBikes' has suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They specifically want to understand the factors affecting the demand for these shared bikes in the American market. So, Linear Regression model is build to anaysis and give the prediction. 


## Business Objective

BoomBikes wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the      demand for these shared bikes in the American market. The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands


## Dataset characteristics

day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


## Steps followed in Linear Regression
* Reading, understanding and visualizing the data
* Preparing data  for modelling - Encoding, Rescaling and Train-Test split
* Training the model on train set
* Residual analysis on Train set
* Prediction and Evaluation on Test set
* Verifying the same with automated approach using RFE


## Conclusions
- Conclusion from the analysis is that top 3 features contributing significantly towards explaining the demand of shared bikes are:
  year, atemp and workingday


## Technologies/Libraries Used
- Python 
- NumPy
- Pandas
- Matplotlib
- Seaborn
- sklearn
- statsmodels.api
- FilterWarnings


## Contact
Created by [@FiscalCoder] - feel free to contact me!