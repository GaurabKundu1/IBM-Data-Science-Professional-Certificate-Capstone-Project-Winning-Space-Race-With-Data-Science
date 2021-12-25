# Winning-Space-Race-With-Data-Science


### Date: 12 th of October 2021  


## Author : [GAURAB KUNDU](https://www.linkedin.com/in/gaurab-kundu-020803) 
 

# Project Description

In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


# Outline 

|       SL. NO        |                                    Outline                                      |
| :-----------------: | :-----------------------------------------------------------------------------: |
|          1          |                              [Executive Summary](https://github.com/GaurabKundu1/IBM-Data-Science-Professional-Certificate-Capstone-Project-Winning-Space-Race-With-Data-Science/blob/main/README.md#executive-summary)                                 |
|          2          |                                 [Introduction](https://github.com/GaurabKundu1/IBM-Data-Science-Professional-Certificate-Capstone-Project-Winning-Space-Race-With-Data-Science/blob/main/README.md#introduction)                                    |
|          3          |                                   [Objective](https://github.com/GaurabKundu1/IBM-Data-Science-Professional-Certificate-Capstone-Project-Winning-Space-Race-With-Data-Science/blob/main/README.md#objective)                                     |
|          4          |                       [Hardware and Software Requirments](https://github.com/GaurabKundu1/IBM-Data-Science-Professional-Certificate-Capstone-Project-Winning-Space-Race-With-Data-Science/blob/main/README.md#hardware-and-software-requirments)                         |
|          5          |                                  Methodology                                    |
|          6          |                  Insights Drawn from Exploratory Data Analysis                  |
|          7          |                        Launch Sites Proximities Analysis                        |
|          8          |                       Build A Dashboard with Plotly Dash                        |
|          9          |                       Predictive Analysis Classification                        |
|          10         |                                  Conclusion                                     |


# Executive Summary

The project is focused on collecting data by web scrapping or API calls, perform EDA and visualize the data before building a classification machine learning models to predict whether the landing will succeed or not.

The results are the plots that show relation of two variables, dashboard, map, and the best classification model is decision tree to predict first stage will be successful or not.


# Introduction

In the age of commercial space travelling, SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.
In this Data Science project we will predict if the Falcon 9 first stage will land successfully, therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


# Objective

## Background
 Reviewing Space X's success in making Falcon 9 rockets with very minimum costs.

 We can analyze SpaceX's data to get the minimum cost to launch a successful rocket for our company.
## Problem
 Predicting whether the first stage land bases on features given.

 Analyzing the features that affect landing success.
## Question for Analysis
 Will the first stage land based on features given?

 Will the features affect landing success?


# Hardware and Software Requirments

## Hardware
In this Project We are going to use IBM Cloud Pack for Data and its various Web services, so a RAM of 8 GB and decent Internet Connection is required only. All the hardware requirments will be covered by IBM Cloud Pack for Data. 
## Software
We are going to use the following softwares in this project :

Programming Language : [Python](https://www.python.org/)

IDE : [Jupyter Notebook](https://jupyter.org/)

Packages : [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html), [Numpy](https://numpy.org/), [Scipy](https://scipy.org/), [Scikit-learn](https://scikit-learn.org/stable/), [Matplotlib](https://matplotlib.org/), [BeautifulSoop](https://pypi.org/project/beautifulsoup4/).


# Methodology

## Data Collection
The data set used in the project is the [SpaceX Lunch data](https://drive.google.com/file/d/1JsDQrujo-qdQPMIdjkXmkzmN8xQIQRig/view?usp=sharing).
