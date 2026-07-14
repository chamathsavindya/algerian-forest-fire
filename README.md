# algerian-forest-fire

- This small project demostrates develop web aplication predicting Fire Weather Index using algerian forest fires dataset.
- Fire Weather Index is a numerical rating system used to predict and  assess the risk of wildfires (forest fires).
- The FWI system uses several weather and fuel variables:
   - Temperature - Higher temperatures increase fire risk
   - Relative Humidity (RH) - Lower humidity dries out fuels
   - Wind Speed (Ws) - Stronger winds spread fires faster
   - Rain - Rainfall reduces fire risk
   - FFMC (Fine Fuel Moisture Code) - Moisture content of fine fuels (grass, leaves)
   - DMC (Duff Moisture Code) - Moisture of loosely compacted organic layers
   - ISI (Initial Spread Index) - Rate of fire spread
   - Classes - Fuel type classification
   - Region - Geographic location

- This project develops Linear Regression model as a base line model and it's compares with Ridge,Lasso and elasticnet models to reduce overfitting and feature selection.
- Finally this project devolops small web application using Flask frame work that gets user inputs and predicts Fire Weather Index. 
