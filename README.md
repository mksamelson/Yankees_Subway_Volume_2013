# Yankees_Subway_Volume_2013
Model to Predict Subway Volume at Yankee Stadium Station in 2013

Data from:  http://web.mta.info/developers/turnstile.html

This dataset shows entry & exit counter values for each turnstile device in each station in the NYC Subway System. 

Modeling

I developed a model for 4hr-interval exit count by station to predict MTA exit volume at Yankee Stadium.  

The model utilizes a Random Forest Regressor.  Attempts to simplify to a linear model were unsuccessful due to a severe decline in performance (attempts to fit a generalized linear model examined are not shown)
