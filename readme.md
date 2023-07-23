## Bike Demand Prediction Project
This project aims to build a multiple linear regression model to predict the demand for shared bikes in the American market. The dataset used for this analysis contains information on various factors that may influence bike demand, such as weather conditions, holidays, and seasons.

### Problem Statement
The bike-sharing provider BoomBikes has experienced a decline in revenues during the Covid-19 pandemic and wants to develop a strategy to accelerate its revenue once the lockdown measures are lifted. The company has partnered with a consulting firm to understand the factors that impact the demand for shared bikes and to identify significant variables in predicting bike demand.

### Dataset
The dataset used for this project consists of daily bike demand data in the American market, along with several independent variables. These variables include year, holiday, season, weather conditions, and other factors that may affect bike rentals.

### Business Goal
The primary goal of this analysis is to model the demand for shared bikes and identify the significant variables that contribute to the variations in demand. By understanding these factors, BoomBikes can adjust its business strategy to meet demand levels effectively and provide an exceptional customer experience.

## Approach
The analysis begins with data exploration and preprocessing, including handling missing values, scaling numeric variables, and creating dummy variables for categorical variables. Feature selection is performed using the Recursive Feature Elimination (RFE) approach, and a multiple linear regression model is built using the selected features.

The model's performance is evaluated using various metrics such as root mean squared error (RMSE) and R-squared. Assumptions of linear regression, including linearity, homoscedasticity, and normality of residuals, are checked to ensure the validity of the model.

### Results and Conclusions
Environmental variables: The analysis considered weather variables such as temperature, humidity, and wind speed (represented by `atemp`, `hum`, and `windspeed` in the dataset). However, these variables did not appear as significant factors in the final model. Therefore, it suggests that these environmental variables may not have a significant impact on bike demand in the American market.
Seasonal variations: The analysis identified the season variable (`season_spring`) as significant factor impacting bike rentals. This indicates that seasonal variations do influence the demand for shared bikes, aligning with your objective to understand the impact of seasonal variations on bike rentals.
Weather conditions: The analysis included weather variables (`weathersit_light_snow`, `weathersit_mist`) and found them to be significant in influencing bike demand. This implies that weather conditions do have an impact on bike rentals, supporting your objective to determine the influence of weather on bike demand.
Holidays and working days: The analysis considered the `holiday` variable, which showed a significant impact on bike demand. This indicates that holidays or non-holidays affect bike rentals, aligning with your objective to explore the factors like holidays or working days influencing bike rentals.
Overall, the results of the regression analysis provide insight into the drivers of bike demand and address the business goals to understand the drivers of bike rentals in the U.S. market.

### Repository Structure
<ul>
    <li>data: Contains the dataset used for the analysis.</li>
    <li>notebooks: Jupyter notebooks used for data preprocessing, feature selection, model building, and evaluation.</li>
    <li>README.md: This file providing an overview of the project.</li>
</ul>

### Instructions
To run the Jupyter notebooks and reproduce the analysis, please follow these steps:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Install the required dependencies by running pip install -r requirements.txt.</li>
    <li>Open the Jupyter notebooks in the notebooks directory and execute the cells sequentially.</li>
</ul>

### Contributors<br>
GitHub Link : https://github.com/anandpbhosale/Linear_Regression_Assignment_Bike_Sharing_System<br>
Anand Bhosale<br>
anandbhosale632@gmail.com