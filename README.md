# SpaceshipTitanic


## Overview 
This project uses machine learning to predict which passengers are transported to an alternate dimension.

This code has been written using Python version 3.7, through an ipynb file using Jupyter notebook. The project notebook is included in this repository and is called ‘Spaceship_Titanic.ipynb’. This will show the fully executed version of all the code used in our project. The data for this project can be accessed on Kaggle.com at the link below. 

https://www.kaggle.com/competitions/spaceship-titanic


## Table of Contents
<a href="#installation">Installation</a>   
<a href="#packages">Packages</a>   
<a href="#notebook-structure">Notebook Structure</a>   


## Installation
You can download the repository by clicking the green ‘Code’ button and selecting ‘Download ZIP’ as seen below. 

<a href="https://ibb.co/K5hVKB4"><img src="https://i.ibb.co/Prj1DJX/download.png" alt="download" border="0"></a>

This will download the relevant Jupyter notebook file ‘Spaceship_Titanic.ipynb’.

In order to use Jupyter Noteboooks, you must have Anaconda downloaded. This can be downloaded from the <a href="https://www.anaconda.com/products/distribution">Anaconda website</a>. For further instruction on downloading Anaconda, please follow <a href="https://www.geeksforgeeks.org/how-to-install-anaconda-on-windows/">this link</a>. 

To open the code, you must first open Jupyter Notebooks. This can be done through Anaconda Navigator, by clicking Launch on Jupyter Notebook as seen below. 

<a href="https://ibb.co/f9GJ1yX"><img src="https://i.ibb.co/Qkj0bTJ/launch.png" alt="launch" border="0"></a>

Once in Jupyter Notebooks, go to the folder where you have saved the file and click to open the file. You will need to extract the zipped folder before opening it in Jupyter. 

## Packages

The necessary packages to run all of the code are found at the top of the Python notebook. 

These include:
- `pandas`
- `matplotlib`
- 'numpy'
- `seaborn`
- `sklearn`
- `xgboost`
- 'lightgbm'


These can be installed by executing the following command in Anaconda Prompt.

`conda install pandas matplotlib numpy seaborn sklearn xgboost lightgbm`


## Notebook Structure
The notebook is divided into 4 sections: data exploration, feature engineering, data modelling and prediction. The entire notebook can be executed at once by pressing Cells > Run All or by typing `Ctrl + A` followed by `Shift + Enter`. Individual cells can be executed with `Shift + Enter`.   

A description of each section and the functions defined in it are given below.

### Data Exploration
This section performs exploratory data analysis on the given dataset, generating summary statistics and approporiate plots of the variables. It also checks for null values and looks at the correlation between variables.
  
### Feature Engineering
In this section, the given variables are transformed in order to improve our model performance. 
  
### Partial least squares regression
This section implements, tunes and compares three models: XGBoost, Light GBM and Logistic Regression. 

### Data Exploration
This section uses the final Light GBM model to predict from the test data set which passengers are transported to an alternate dimension
