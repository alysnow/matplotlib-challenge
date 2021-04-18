# matplotlib-challenge
Week 05 - Homework

## Matplotlib Homework - The Power of Plots

## Background

As the senior data analyst at Pymaceuticals Inc.,a pharmaceutical company based out of San Diego which specialises in anti-cancer pharmaceuticals. I have been given access to the complete data from the most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured.

The purpose of this study is to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study and provide a top-level summary of the study results.

## Overview

The final report includes each of the following using Pandas and Jupyter notebook to write the code, create data frames and supporting charts.

* Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Potential outliers across all four treatment regimens, Capomulin, Ramicane, Infubinol, and Ceftamin.

* Box and whisker plot of the final tumor volume for all four treatment regimens, highlighting any potential outliers in the plot.

* Line plot of tumor volume vs. time point for for a mouse treated with Capomulin.

* Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.

##  Observation Summary

1. Drug regimen Capomulin has the highest number of mice (230), while Propriva has the least number of mice (161).

2. A total of 124 female mice and 125 male mice were included in the total count of mice by gender with the total number of mice after duplicates were removed totalling 248 mice.

3. The average tumour volume and mouse weight have a correlation of 0.84. It's a good positive correlation. As the weight of the mouse increases, so does the average tumour volume.

4. Regression analysis was applied to figure out how much the average tumour volume (dependent variable) would change as the weight of the mice changes (independent variables). The R-squared value is 0.70, indicating that the model fits the data 70% of the time, which is a strong indicator of the model's ability to predict data. Smaller variations between the observed data and the fitted value are represented by higher R-squared values 70% of the time.