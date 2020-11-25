# Isaac Medina's Python API Homework 

## Background

This repository Hosts Isaac Medina's work for the PythonAPI's Challenge. Working with the openweather API and a couple of python modules we create two separate analyses that answer 2 questions: 
1.  What happens to the weather as one moves toward the equator?
2.  What are the best Hotel's to stay at across the world according to our weather preferences? 

![Equator](Images/equatorsign.png)


## Dependencies
*Python
*Jupyter Notebooks
*Matplotlib
*Numpy
*Google Maps API
*Jupyter gmaps


## Files

In the folder 'startercode' you will find the following two analyses: 

### WeatherPy
A Python script to visualize the weather of 500+ cities across the world utilizes the module [simple Python library](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api). 


### Part II - VacationPy

Uses the weather data from cities in first part of the analysis (WeatherPy) to 
* Narrow down the DataFrame to find 5 top cities with my ideal weather condition. 

* Utilized the Google Places API to find the first hotel for each city located within 5000 meters of coordinates.

* Plots the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.


## Other Files
* screenshots of the scatterplots and the Hotel Map saved in the 'screenshots' folder

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
