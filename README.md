# Seattle-Weather
Seattle and St. Louis Weather Data from National Centers for Environmental Information from NOAA, from January 1, 2017 to December 31, 2022

This repository is to create a dataset for the analysis steps of the data science methodology to answer the question of whether it rains more in Seattle, WA than in St. Louis, MO.

The original datasets containing SEA and STL precipitation data were cleaned and merged together to form one combined dataset that only includes the data from one SEA station and one STL station, and only the precipitation and dates were included in the new dataframe with the cities. Missing values in the dataset were replaced by the mean precipitation value for that day.

The python notebook that performs the data preparation is in this repo: https://github.com/pintoanabel/Seattle-Weather/blob/main/APPrep_DATA_3320_Seattle_St_Louis_Data_Preparation%20(1).ipynb

the clean csv is also in the repo: https://github.com/pintoanabel/Seattle-Weather/blob/main/clean_seattle_stl_weather.csv

