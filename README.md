# ML_Bike_Sharing_Demand_Prediction_Regression
![Bike sharing](https://github.com/Sachinvt/ML_Bike_Sharing_Demand_Prediction_Regression/assets/140580938/028a6aab-c359-4f77-a8fd-0599df829af9)
# Project Summary -
**BUSINESS PROBLEM OVERVIEW**-
Urban cities are experiencing an increasing need for efficient and sustainable transportation solutions to address traffic congestion and environmental concerns. In this context, rental bikes have gained significant popularity as a cost-effective and eco-friendly mode of transportation. These bike-sharing systems provide city residents and tourists with a convenient and accessible means of commuting.

However, ensuring a stable supply of rental bikes is a complex challenge. The success of a bike-sharing system relies on predicting the demand accurately at various hours and locations, to ensure that bikes are available when and where needed. This problem statement aims to address the task of predicting bike-sharing demand, which plays a crucial role in maintaining an efficient and reliable bike-sharing system

# Datasets:

The dataset you described contains information related to bike sharing and includes various attributes:

**Date:** The date in a year-month-day format.

***Rented_Bike_Count:** *The number of bikes rented at each hour. This is the target variable you might want to predict.

**Hour:** The hour of the day, indicating the time at which the bike rentals are recorded.

**Temperature:** The temperature in Celsius at the given time.

**Humidity:** The humidity level expressed as a percentage.

**Windspeed:** The wind speed in meters per second (m/s).

**Visibility:** The visibility in meters (typically given as 10 meters).

**Dew Point Temperature:** The temperature at which air becomes saturated and dew forms, typically in Celsius.

**Solar Radiation:** Solar radiation measured in MJ/m2 (MegaJoules per square meter).

**Rainfall:** The amount of rainfall in millimeters (mm).

**Snowfall:** The amount of snowfall in centimeters (cm).

**Seasons:** A categorical variable indicating the season at the given date and time, such as Winter, Spring, Summer, or Autumn.

**Holiday:** A categorical variable indicating whether it's a holiday or not (Holiday/No holiday).

**Functional Day:** A categorical variable indicating whether it's a functional day (Functional hours) or a non-functional day (Non-Functional Hours).

Basically this dataset consist of 8760 rows and 14 columns. It also having no any duplicate or missing values. Out of 14 variables there are 4 categorical features and remaining are numerical features.

# Conclusion
we can draw several conclusions regarding bike rental demand:

Random Forest and XGBoost models shows promising result, therefore it can be used to solve this problem.

**Day of the Week:** Bike rental counts are higher on weekdays than on weekends. This suggests that people are more likely to use bikes for commuting or daily activities during the workweek, while on weekends, recreational bike usage might be more prevalent.

**Peak Hours:** The peak hours for bike rental demand occur in the morning (around 8-9 AM) and in the evening (around 6-7 PM). These times align with typical commuting hours, indicating that many people use bikes for their daily commute.

**Seasonal Variation:** Bike demand is higher in summer than in winter. This is expected, as more people are inclined to rent bikes when the weather is warm and pleasant. In contrast, cold winter weather may discourage bike usage.

**Weather Conditions:** Bike demand is higher on clear days compared to snowy or rainy days. People tend to avoid biking in inclement weather, which can be less safe and comfortable.

**Temperature Range:** The temperature range of 22 to 25°C is associated with higher bike rental demand. This indicates that mild and comfortable temperatures are preferable for bike riders. Extreme cold or hot weather may deter people from renting bikes.

**Relevant Features:** The features that influence bike demand include 'Hour,' 'Temperature(°C),' 'Humidity,' 'Wind_speed,' 'Visibility,' 'Dew_point_temperature,' 'Solar_Radiation,' 'Rainfall,' 'Snowfall,' 'Seasons,' 'Holiday,' 'month,' and 'day of the week.' These factors are essential for predicting and regulating bike rental demand.

Based on these conclusions, it would make sense to use machine learning models like Random Forest and XGBoost to predict bike rental demand, as they can effectively capture the relationships between these features and the demand for bike rentals. These models can help businesses optimize their bike rental services by forecasting demand and making data-driven decisions, such as adjusting the number of available bikes, pricing, and marketing strategies to meet the needs of their customers.
