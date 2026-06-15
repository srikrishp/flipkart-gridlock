# Flipkart-gridlock

Traffic Demand Prediction – Solution Summary

Approach:

* Used CatBoost Regressor for demand prediction.
* Handled missing values using median (numerical) and "Missing" (categorical).
* Extracted hour, minute, and time_slot from timestamp.
* Used categorical features such as geohash, RoadType, Weather, LargeVehicles, and Landmarks.
* Trained CatBoost model and generated predictions for the test dataset.

Tools Used:

* Python
* Pandas
* CatBoost
* Google Colab

Final Public Score:

* 90.43837
