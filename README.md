# Python API Challenge: WeatherPy and VacationPy

Overview
This repository contains the Python API Challenge, a two-part project designed to explore weather patterns and plan vacations using Python, APIs, and data visualization tools. The project leverages the OpenWeatherMap API, Geoapify API, and the citipy Python library to analyze weather data across 500+ cities and create visualizations that reveal relationships between weather variables and geographic locations.

Project Structure
The challenge is divided into two main parts:

Part 1: WeatherPy
In this section, we analyze weather data to answer the question: "What is the weather like as we approach the equator?" Using the OpenWeatherMap API, we generate weather metrics for cities worldwide and perform the following tasks:

Create Scatter Plots:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Compute Linear Regressions:
- Analyze relationships for the above metrics, separating data into Northern and Southern Hemispheres.
- Include regression lines, formulas, and r² values to highlight trends.

Part 2: VacationPy
This section uses weather data to plan ideal vacation spots. Tasks include:

1. Creating a map to display humidity data for each city.
2. Narrowing down cities based on ideal weather conditions (e.g., temperature range, wind speed, cloudiness).
3. Using the Geoapify API to locate the first nearby hotel for each selected city within 10 kilometers.
4. Displaying a detailed map with hover messages showing hotel names, locations, and weather information.

Repository Contents

Notebooks:
- WeatherPy.ipynb: Jupyter Notebook containing the analysis and visualizations for Part 1.
- VacationPy.ipynb: Jupyter Notebook with the vacation planning workflow in Part 2.

Data:
- api_keys.py: Stores API keys for OpenWeatherMap and Geoapify (excluded via .gitignore for security).

Outputs:

Visualizations:
- Fig1.png: Scatter plot - Latitude vs. Temperature.
- Fig2.png: Scatter plot - Latitude vs. Humidity.
- Fig3.png: Scatter plot - Latitude vs. Cloudiness.
- Fig4.png: Scatter plot - Latitude vs. Wind Speed.

Data:
- cities.csv: CSV containing city weather data for visualization.

Additional:
- .gitignore: Ensures sensitive files, such as api_keys.py, are not tracked.
- README.md: Documentation and project overview (this file).

Results and Insights
- Weather Trends: Temperature decreases as you move away from the equator. Other metrics, such as humidity and cloudiness, showed varied but ultimately inacctionable relationships.
- Vacation Planning: Identified cities with ideal weather conditions, mapped nearby hotels within 10 kilometers for those possible, and created a user-friendly visualization for vacation recommendations.