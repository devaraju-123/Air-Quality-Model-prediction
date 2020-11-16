# Air-Quality-Model-prediction
Air Quality Index Complete End to End Project.

Project Description: Global climate data is a Climate Information for every country in the world with historical data in some cases date back to 1929. Hear we use 2013 to 2019 India climate data in state of Bangalore city. we can predict air quality index in this project. Hear the machine learning model predict the PM2.5 ratio.

Interpretation annual average climate values

• T Average annual temperature • TM Annual average maximum temperature • Tm Average annual minimum temperature • PP Rain or snow precipitation total annual • V Annual average wind speed • RA Number of days with rain • SN Number of days with snow • TS Number of days with storm • FG Number of foggy days • TN Number of days with tornado • GR Number of days with hail

Data Source: https://en.tutiempo.net/climate

Machine Learning pipeline:

Data Gathering: In this step we can take the data from https://en.tutiempo.net/climate. Tools used : html, Beautiful Soup python library.

Feature Engineering: handling null values, find the correlation between independent and dependent variables, heatmap.

Feature Selections: for selecting right feature using ensemble model ExtraTreesRegressor.

Model building: Linear Regressing, random Forest regression (Non-Liner Classifier), Xg boost etc.

Model tuning: Hyperparameter tuning RandomForestRegressor.

Model Deployment: flask and Heroku.

Here is the link where you can access the project live : https://airqualityaqiapp.herokuapp.com

Thank you!
