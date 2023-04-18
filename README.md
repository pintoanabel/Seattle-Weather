# Seattle-Weather
Seattle and St. Louis Weather Data from National Centers for Environmental Information from NOAA, from January 1, 2017 to December 31, 2022

**Description:**

This repository is to create a dataset for the analysis steps of the data science methodology to answer the question of whether it rains more in Seattle, WA than in St. Louis, MO. Precipitation data for the cities of Seattle and St. Louis were compared across a span of 5 years, from 2018 to 2022. It was concluded that while it rains more days in Seattle, it rains heavier in the city of St. Louis.

**Requirements:**

No installed software was used for this project. Google Colab was utilized as the host environment for Python, which requires no software installation.

**Data:**

Weather data gathered from NOAA Climate Data on the amount of precipitation in the cities of Seattle, WA and St. Louis, MO from from January 1, 2017 to December 31, 2022.

Source Data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

Seattle Weather Data csv raw link: https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/seattle_rain.csv
St. Louis Weather Data csv raw link: https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/stl_rain.csv

**Data Processing:**

The original datasets containing SEA and STL precipitation data were cleaned and merged together to form one combined dataset that only includes the data from one SEA station and one STL station, and only the precipitation and dates were included in the new dataframe with the cities. Missing values in the dataset were replaced by the mean precipitation value for that day.

The python notebook that performs the data preparation is in this repo: https://github.com/pintoanabel/Seattle-Weather/blob/main/APPrep_DATA_3320_Seattle_St_Louis_Data_Preparation%20(1).ipynb

the clean csv is also in the repo: https://github.com/pintoanabel/Seattle-Weather/blob/main/clean_seattle_stl_weather.csv

the cleaned precipitation data was then analyzed. the number of days for each city without any recorded rainfall was calculated and graphed, as well as the number of days where each city experienced at least 1.5 inches of rainfall. the monthly and yearly precipitation averages for each city over the 5 year span were also calculated. dataframes were created for each subset of data to generate the corresponding graphs, all taken from the cleaned data csv.

the python notebook that performs the data analysis is in this repo: https://github.com/pintoanabel/Seattle-Weather/blob/main/APAnalysis_Seattle_St_Louis_Analysis_Template.ipynb

**Authors:**

The author of this repository and its contents is Anabel Pinto
LinkedIn: https://www.linkedin.com/in/anabel-pinto/

**License:**

GNU GPLv3 (GNU General Public License v3.0)
