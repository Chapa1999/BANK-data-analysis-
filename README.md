# BANK-data-analysis

# INTRODUCTION
● This data set is related to a Portuguese banking institution’s marketing campaign. The marketing campaigns were based on telemarketing. 
● The contact information includes date, time and number of contacts made to a customer in order to get the response of “yes” or “no” to their term deposit.

## This repository consists of the following:
README.txt (this file)
Dataset : "Data.xlsx"
Notebook downloaded as an ipynb file
"Bank" consists of  all the data analysis And try to solve the some statistical problem.

# Step 1 : IMPORTING LIBRARIES:
### We are import many libraries as per our needed:-
import pandas as pd                 # used for data analysis.
import numpy as np                  # used to perform mathematical operations on arrays.
import matplotlib.pyplot as plt     # used to collection of command style functions that make matplotlib work like MATLAB.
import seaborn as sns               # used to python data visualization library based on matplotlib.
import missingno as msno            # used to understand the distribution of missing values through informative visualizations.
from scipy import stats             # used to solve scientific and mathematical problems.
import warnings                     # used to terminates immediately if an error occurs.
warnings.simplefilter(action = "ignore")
from tabulate import tabulate       # used to print tabular data in nicely formatted tables.
from termcolor import colored       # used for ANSII Color formatting for output in the terminal.

# Step 2: Clear the data
1. We clear a lot of things  as per understanding data.
2. Also we doing missing value treatment.
3. Change the data type as per our requirement.

# Step 3: DATA ANALYSIS
#### 1. Univariate Analysis:-
      In this case there are two part . First one categorical Data Analysis and Second one Numerical Data Analysis. 
        ● In Categorical Data Analysis we are using Barplot, Pieplot, Countplot etc 
        ● In Numerical Data Analysis we are using Boxplot, Kdeplot, Distplot, Histogram etc  
##### We are plotting each column individually to clearly understand the column dataset using Univariate Analysis.
#### 2. Bivariate Analysis
       In this case there are three part . First one Categorical Vs Categorical , Second one Categorical Vs Numerical And Third one Numerical Vs Numerical.
           ● In Categorical Vs Categorical Data Analysis we are using Chi_Square_Test, Crosstab etc.
           ● In Numerical Vs Categorical Data Analysis we are using barplot,boxplot etc.
           ● In Numerical Vs Numerical Data Analysis we are using scatterplot.
##### We are using bivariate analysis to compare between the two columns.
#### 3. Multivariate Analysis
##### Multivariate analysis is about simultaneously finding patterns and interrelationships between different variables.
# Step 4 : SUMMARIZING THE DATASET
Dimensions of the dataset
Peek at the data
Statistical Summary
Class Distribution
Information about data
Length of the data
# Step 5 : Outlier Treatment
● Outlier is an observation that is abnormally distant from other values ​​in a random sample from a population.
● First we are checking all the numeric columns to see if Outlier is present. If present then try to remove outlier using some technique.
# Step 6 : Statistics Manipulations
1. Find the correlation between the columns and draw the observations from it.
► We can observe that there is no   strong relation for any columns ,only  pdays & coustomerid  (0.44) and pdays & previous (0.45) relation each other . 
2. Find the mean of every column response wise and draw the observations. 
► It shows the response wise mean of every categorical columns . age &response yes having mean value 41.67 and age & response no having mean value 40.84 and many more 
3. Find the Best features using correlation and Chi-square test.
► We can reject our H0 in every case expect coustomerid & response and year & response means they are independent each other.
4. Find the relation of salary and age column using statistical tests and draw the observations from it.
► WE can observe that age between 30-49 have more salary and range of the salary 60000-120000 & Age 90-95  salary range is 30000-60000.

# Thank You
