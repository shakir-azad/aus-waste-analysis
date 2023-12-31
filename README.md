# Analysis of waste data in Australia from 2016-2019
## Overview
With the growing concerns surrounding climate change, humanity, ranging from global to individual level needs to make an effort to meet sustainability goals set by world leaders. Analyzing how waste is treated and generated in Australia will provide insights that will help increase the efficiency of the process and allow us to work towards the goal.   
  
In this project, we sourced the waste data from the Australian Bureau of Statistics for the years 2016-2019 (which was the latest data available at the time of the project). We used PowerBi and employed the ETL process to analyze the dataset, extract insights, and produce visualizations.

## About the dataset
The Waste dataset is separated into 2 files, one containing data from 2016-2017 and the other from 2018-2019. Each file contains several tables containing information about different waste categories and their generation and usage.

## Process
Followed the ETL process by first extracting all the datasets onto PowerBi, then transformed the datasets by carrying out initial cleaning like changing types and filling out missing values. Created a new dimension table containing different years and formalized relationship with the facts table containing event details. After a few more transformative steps like splitting and deleting columns, the dataset was loaded and visualizations were created. 

## Conclusion
The visualizations were used to answer two main questions: 'Which waste categories have been the driving force behind the trend in supply-usage across 2016-2019?' and 'Which industry statistics should we track to track the performance of the agricultural industry in waste management?'
