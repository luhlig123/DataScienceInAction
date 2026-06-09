# Data Science in Action
Author: Leo Uhlig

## Purpose
The purpose of this repository is to explore and analyze call volume data from the Eugene/Springfield police departments, CAHOOTS, and MCSLC. In its current form, this repository takes call data from each agency and and returns simplified DataFrames representing the number calls each agency recieved between 2015 and 2025. This repository also generates simple visualizations to display differences in call volume between agencies depending on which city they serve.

In the future, this repository will also be capable of conducting differences in differences analysis to examine how the closure of CAHOOTS in Eugene has has impacted the call volumes of the Eugene police department and MCSLC.

## requirements
packages:

- numpy
- pandas
- datetime
- seaborn
- matplotlib
- statsmodel