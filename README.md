Team NM4_DS_Projects
==============================

# Spain Electricity Shortfall Challenge

## Project Organization
------------

    
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original data for modeling.
    │
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── images             <- Graphics and figures to be used
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment.
    │



==============================


## Dataset Description

This dataset contains information about the weather conditions in various Spanish cities for the time of 2015-2017. The dataset also has information about the three hourly load shortfalls for the same period. In the context of this problem, the three hourly load shortfall is the difference between the energy generated by means of fossil fuels and renewable sources.

The dataset contains 47 features and 1 target. The features include the time and the city-specific weather variables i.e. the wind speed in the city of Barcelona. In total there is weather data available for 5 cities but not all cities have weather information available for every weather category e.g. we might have wind speed data for Barcelona but not rainfall data whereas we have both rainfall and wind speed information for Valencia.

### We have weather data for the following cities of Spain:
- Madrid
- Valencia
- Seville
- Bilbao
- Barcelona

### The weather categories in the dataset include:

- wind_speed
- wind_degree
- rain_1h
- rain_3h
- humidity
- clouds_all
- pressure
- snow_3h
- weather_id
- temp_max
- temp

## File descriptions

- **df_train.csv** - the training set
- **df_test.csv**  - the test set
- **sample_submission_load_shortfall.csv** - a sample submission file in the correct format

## Features

Below follows a brief description of the features and targets contained in the dataset.

- **time:** Time at which the data was recorded
- **{City Name}_wind_speed:** The wind speed at a specific time interval for the named city.
- **{City Name}_wind_degree:** The strength of the wind for the named city at a specific time interval -       expressed as a category.
- **{City Name}_rain_1h:** A metric expressing the amount of rain that has fallen in the past hour in a particular city.
- **{City Name}_rain_3h:** A metric expressing the amount of rain that has fallen in the past three hours in a particular city.
- **{City Name}_humidity:** The level of humidity as measured at the defined time for the specific city mentioned.
- **{City Name}_clouds_all:** The level of cloud coverage as measured at the specified point in time for the specific city mentioned.
- **{City Name}_pressure:** The atmospheric pressure for the named city at a specific time interval - expressed as a category.
- **{City Name}_snow_3h:** A metric expressing the amount of snow that has fallen in the past three hours in a particular city.
- **{City Name}_weather_id:** A metric used to explain the weather condition of a specific city at a specified time.
- **{City Name}_temp_max:** The maximum temperature for a specific city at a point in time.
- **{City Name}_temp_min:** The minimum temperature for a specific city at a point in time.
- **{City Name}_temp:** The average temperature for a specific city at a point in time.

## Target Variable
- **load_shortfall_3h:** The difference between the energy generated by the method of renewable energy sources, such as solar, wind, geothermal, etc., and energy generated with fossil fuels - partitioned in three-hour windows.




## 
    


--------


