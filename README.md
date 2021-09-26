# udacity_advanced_data_analysis_ND_project_3
the data we choose is 2008 expo data set which consists of data for flight arrival and departure details for all commercial flights within the USA in 2008 

## dataset insights
- the data set is too large (7M observations) we might need to sample it to reduce the time of visualize
- the data have alot of missing data but this is because alot of the flights isn't cancelled or delayed and there is multple features about cancilation and delay

## Univariate Exploration insights 
- july have the highest number of flights  
- October have the lowest number of canceled flights but February have the highest number of canceled flights
- saturday has the least number of flights 
- saturday has the least number of cancelled flights 
- day 31 have the least number of flights in the year which is predictable as not all months contain 31 days
- day 4 has the hieghest number of cancelled flights
- WN carrier has the highest number of flights
- MQ carrier has the highest number of cancelled flights
- most of the continuous features are skewed to the rights and there is no gaussian distribution
- 2% of flights are cancelled
- 0.25% of flights are diverted
- most of flights (80%) are cancelled beacuse of weather of carrier reasons

## Bivariate Exploration 
- there are some strong positive correlation between arrival delay and departure delay 
- Distance and Elapsed time are strongly correleted
- some features has alot of outliers 

## Multivariate Exploration 
- months like april and may cancillation reasons is too low for B (weather) as the weater is these monthes is the best , also the cancellation reason for months like december and january and february increases for weather as the weather in these months isn't the best for flights

## Modeling 
can we predict if a fligh be cancelled or not ??, we will use logistic regression to predect so
logistic regression accuracy is 0.9999191599866661 
