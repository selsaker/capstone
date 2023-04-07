## Capstone 

## Overview
Dataset from GHO was utilized to extract the correlation between our target variable life expectancy and dependant variables 'Schooling' and 'Alcohol.'

We are trying to predict the target life expectancy through these two dependant variables.

- Link to PPT: https://github.com/selsaker/capstone/blob/main/Develop_Countries_Final_Presentation.pptx

- Link to Code: https://github.com/selsaker/capstone/blob/main/develop_countries_code.ipynb

## About this Dataset
- The data is sourced from The Global Health Observatory (GHO) data repository under World Health Organization.
This data is from the time period of 2000 to 2015.
- In a nutshell, this data consists of immunization factors, mortality factors, economic factors, social factors and other health related factors.
- Due to time constraints, this dataset is already prepopulated and found online.
- Features include life expectancy, infant deaths, BMI index, population, HIV/AIDS, schooling, and much more.


### What packages did we use?
 - Matplotlib
 - Pandas
 - SQL (SQLITE3)
 - Numpy
 - Seaborn
 - Scipy.Stats
 - Sklearn
 
 ## Business Understanding
### Current Situation 
Currently, the world has a large population of individuals in developing countries. This study is meant to explore where funding should be put to improve the longutivity and quality of life for this population.

### How are we doing it?
We will be reviewing life expectancy as our numerical way of measuring health quality and longevity. The other data columns will be the independant factors. The two factors we will be focusing on are Schooling and Alcoholism. This was chosen because we wanted to have 1 external independant variable and 1 internal independant variable. External meaning outside the body and internal as in inside the body. 

The 3D analysis includes life expectancy vs schooling and alcoholism
The 2D analysis includes life expectancy vs schooling

## Data Understanding Analysis 
This analysis has a 2D and 3D Portion.

In the 3D portion, we look at the R Squared value, skew, and other results of our regression. This regression was between life expectancy vs. schooling. We use visualizations such as histograms, Q-Q plot to better understand the results of the analysis as well. 

In the 2D portion, we look at the MSE and other results of the test and train of our regression. This regression was between life expectancy vs. schooling and alcoholism.



## Statistical Communication 
3D
- MSE for train is 40.37 and MSE for test is 41.39. This shows that their is an improvement in our model prediction.

- Normalized MSE is 0.14. The closer the 0 the better the performance.

2D
- Our regression line for our 2D exploration is y = 0.23159 x  - 4.38385
- R squared value is 0.44, which means 44% of the variation in Y (life expectancy) is explained by out model.
- Skew is -0.414, which means it is skewed to the left


