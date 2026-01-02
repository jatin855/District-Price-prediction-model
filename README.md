# District Price Prediction Model
This project is a machine learning initiative designed to predict median house values at the district level. It analyzes various demographic and geographic features to estimate housing prices, serving as a prototype for real estate price regression.

## Project Overview
### 1. Goal: 
To accurately regress and predict the median_house_value for different districts based on census data.

### 2. Dataset: 
Utilizes the California Housing dataset, including features such as:

       median_income

        housing_median_age
        
        total_rooms / total_bedrooms
        
        population / households
        
        ocean_proximity
        
        Location (latitude, longitude)

### 3. Tech Stack: 
The project is notable for its use of RAPIDS libraries (cuDF, cuML) alongside scikit-learn to leverage GPU acceleration for faster data processing and model training.

### Key Components:

#### Data Analysis: 
Includes histograms and statistical summaries to understand data distributions (e.g., income, housing age).

#### Preprocessing: 
Handles train/test splitting using unique identifier hashing to ensure consistent data separation.

#### Modeling: 
Implements regression algorithms to minimize Root Mean Squared Error (RMSE) and save the final optimized model (Prototype_district_prices_predictor.joblib).
