Table of Contents
General Info
Technologies Used
Conclusions
Acknowledgements

General Information
Project Description: This project analyzes the factors affecting the demand for bike-sharing services in a city. The aim is to build a linear regression model to predict the number of bikes rented based on various weather and seasonal factors.
Background: Understanding the factors influencing bike-sharing demand can help service providers optimize their operations and improve customer satisfaction.
Business Problem: The goal is to accurately predict bike demand to ensure sufficient supply during peak times and minimize idle resources during off-peak times.
Dataset: The dataset used includes daily bike-sharing counts along with various features such as date, season, weather, and holiday information.

Conclusions
The linear regression model achieved an R-squared value of 0.828 on the training set, indicating a good fit.
The most significant features influencing bike demand were year, temp, and Light_snowrain.
Negative coefficients, such as windspeed and Light_snowrain, indicate that higher values of these variables are associated with a decrease in bike rentals.
The model validation on the test set highlighted the need for proper data scaling and feature selection to avoid overfitting and improve predictive performance.

Technologies Used
Python - version 3.8
Pandas - version 1.2.3
NumPy - version 1.19.2
scikit-learn - version 0.24.1
statsmodels - version 0.12.2
Matplotlib - version 3.3.4
Seaborn - version 0.11.1