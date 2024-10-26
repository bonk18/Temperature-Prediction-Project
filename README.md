

# Seoul Daily Temperature Prediction using LDAPS Model  

This project leverages the LDAPS (Local Data Assimilation and Prediction System) model dataset to analyze and predict daily temperatures in Seoul, South Korea. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling to enhance insights and forecasting accuracy for Seoul's temperature patterns.

## Project Overview:   
The goal of this project is to predict daily maximum and minimum temperatures in Seoul using historical weather data provided by the LDAPS model. This analysis provides valuable insights into temperature trends and helps improve forecasting accuracy for specific days.  

##  Dataset Information
The dataset used in this project includes the following features:

- Geospatial data: Latitude, Longitude.  
- Meteorological data: Daily minimum and maximum temperatures, atmospheric pressure, lapse rate, humidity, and other environmental factors.  
- The data was sourced from LDAPS, a high-resolution weather prediction model that provides daily predictions.  

## Project Workflow  

### - Data Preprocessing:  
Conversion of date information to datetime format for better handling and analysis.
Handling of missing values, outlier removal (based on IQR), and data transformation for feature scaling.  

### - Exploratory Data Analysis (EDA):
Visualizing distributions and relationships between meteorological features.
Identifying and handling outliers in continuous variables to improve model accuracy.  

### - Feature Engineering:
Calculating additional metrics such as lapse rate.
Applying Principal Component Analysis (PCA) to reduce dimensionality while retaining 95% of variance.

### - Modeling:  
Trained and evaluated multiple models, selecting the one with the best performance for temperature prediction.
Model evaluation metrics included MAE, MSE, and R² score to measure prediction accuracy.  

### - Results and Insights:  
Evaluated model performance, and visualized actual vs. predicted temperatures.
Identified key factors influencing daily temperature variations in Seoul.
Results
The final model achieved a high accuracy in predicting daily temperature variations in Seoul. 


## License  
This project is licensed under the MIT License.
