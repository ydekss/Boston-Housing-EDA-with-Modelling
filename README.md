# Boston-Housing-EDA-with-Modelling

In this project I have taken the most famous Boston Housing Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualize them. I've also fitted a multiple linear regressor that predicts the price of the houses.

  

![alt text](https://cdn10.bostonmagazine.com/wp-content/uploads/sites/2/2022/06/housing-costs-story.jpg)

  
  

# Exploratory Data Analysis and Multiple Linear Regression on Boston Housing Dataset

This dataset contains information about 506 census tracts of Boston from the 1970 census. As an aspiring data scientist, understanding how to model data like this is of great importance to me. In this kernel, I will use the Boston housing data by Harrison and Rubinfeld (1979) and explore which factors affect the median value of homes. I will perform a linear regression analysis on the same.

  

## Boston Housing Data

The data has following features, medv being the target (dependent) variable:

  

- crim - per capita crime rate by town

- zn - proportion of residential land zoned for lots over 25,000 sq.ft

- indus - proportion of non-retail business acres per town

- chas - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

- nox - nitric oxides concentration (parts per 10 million)

- rm - average number of rooms per dwelling

- age - proportion of owner-occupied units built prior to 1940

- dis - weighted distances to five Boston employment centres

- rad - index of accessibility to radial highways

- tax - full-value property-tax rate per USD 10,000

- ptratio - pupil-teacher ratio by town

- black - proportion of blacks by town

- lstat - percentage of lower status of the population

- medv - median value of owner-occupied homes in USD 1000’s

  

## We will structure the code as follows

1. Loading the data

2. Preparing the data

3. Exploratory Data Analysis

4. Building the model and accuracy analysis

5. Final Analysis of the model

## These are some of the insights
![Insight Images - Free Download on Freepik](https://img.freepik.com/free-vector/gradient-insights-illustration_23-2149322241.jpg?w=2000)
-  The median value of owner-occupied homes in the Boston suburbs ranges from $5,000 to $50,000, with a mean of $22,533.
- The distribution of the median value of homes is slightly right-skewed, with a few suburbs having very high median home values (up to $50,000).
- The variables that have the strongest positive correlation with the median value of homes are the average number of rooms per dwelling and the proportion of residential land zoned for lots over 25,000 square feet.
- The crime rate per capita variable has a skewed distribution, with a few suburbs having a very high crime rate compared to others.
- The Charles River dummy variable (which indicates whether a suburb borders the river or not) has a significant impact on the median value of homes, with suburbs that border the river tending to have higher median home values.

## Modelling
I have also fitted a Linear Regression model which predicts the price of the house, feel free to look at the `ipnyb` file to explore more.

![22 Ways to Say Thank You in Chinese That Suit Any Situation](https://i0.wp.com/www.writtenchinese.com/wp-content/uploads/2016/12/22-Ways-to-Say-Thank-You-in-Chinese-That-Suit-Any-Situation.png?resize=800%2C350&ssl=1)



  


