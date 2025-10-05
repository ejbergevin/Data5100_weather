# Weather: Precipitation Across Cities of Seattle and Springfield
> This project seeks to answer the question of whether it rains more in Seattle, WA or Springfield, OR.

---

## Project Overview

This project seeks to answer the question of whether it rains more in Seattle, WA or Salem, OR.

- **Objective:** Determine which city is rainier
- **Domain:** Weather
- **Key Techniques:** Descriptive approach through statistic and visualization comparison

---

## Project Structure

This project compares daiy precipitation data from NOAA NCEI collected at local weather stations between 01-01-2018 and 12-31-2022 in Seattle, WA and Springfield, OR. Please see data within the 'data' folder: Seattle raw data 'seattle_rain.csv', Springfield raw data 'springfield_rain.csv', final data source 'clean_seattle_springfield_weather.csv'.

Data cleaning and processing was completed in python. Please see the notebook 'Weather_Data_Processing.ipynb' within the 'code' folder. Data can be independently requested at https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND.

Summary statistics, graphic visualization, and conclusion have been transfered to a pdf report. Please see the file within the 'reports' folder.

---

## Data Processing

Data from NOAA NCEI consists of precipitation collected at one station in Seattle, WA, 01-01-2018 to 12-31-2022, and at 68 stations in Springfield, OR over the same dates.

Cleaned data consists of only one station's worth of records from both cities. Precipitation values for several dates from each city over the five year period were missing; these have complemented by the mean average precipitation for that day of the year for that city. Both data sets were combined into one tidy final source. Several variables transforming date were introduced to better visualize trends. Line plots, bar plots, and histograms were generated for ease of visualizing findings.