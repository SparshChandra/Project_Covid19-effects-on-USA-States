# Project_Covid19-effects-on-USA-States
# Data Analysis of COVID-19 Effects on USA States
## About The Project
![Screenshot 2023-09-11 at 3 04 18 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/ad522b28-8ced-4cea-bf92-7c922d75e404)

One event dominated in 2020: a deadly and previously unknown virus wreaked havoc across the globe, killing more than 1.5 million people, infecting many more and causing economic
devastation.

* The pandemic set the course of science to an extraordinary degree. Across the United States, COVID-19 infections and deaths were surging
* California, New York, Florida, Texas, and New Jersey were amongst the worst-hit states
* Based on the chosen dataset, we are trying to compare COVID-19 statistics for California state versus New York state

![Screenshot 2023-09-11 at 3 06 54 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/728e182b-63ad-40b3-969b-9dfeabcf7845)


## Dataset Overview

The dataset used in this analysis is from January 2020 to March 2021, and it depicts how COVID-19 affected all 50 states in the US throughout the epidemic.

* Dataset volume : 3 MB
* Number of rows: 20,780
* Number of columns: 41

* The fundamental reason for selecting this dataset is that the COVID-19 outbreak had a huge impact on the world for the past two years and it continues to do so.

* From vaccines and treatments to lockdowns and virtual reality, the coronavirus epidemic altered the year in research.

  ![Screenshot 2023-09-11 at 3 10 00 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/f95d1123-5298-45f3-806f-7d893e6762f6)

## Tableau Represtentation

![Screenshot 2023-09-11 at 3 10 53 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/8614fc12-e3cb-487b-9fbe-643c79b8d730)

* As the graph suggests, the maximum number of tests done, and positive cases were found in California New York
* Comparing these two states we are evaluating the relationship between the following parameters:
   Number of total tests results, 
   Number of positive cases, 
   Number of hospitalized currently, 
   Number of deaths.

  ## Descriptive Statistics: Key Variables
  ### Total Test Results
* Ratio data Counts the total number of COVID-19 tests conducted on each state population.

  
  #### California
  
  * Mean: 15808631
  * Standard deviation: 15138231
 
  #### New York
  
  * Mean: 12264133
  * Standard deviation: 11600514
 
  
  ![Screenshot 2023-09-11 at 3 17 51 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/628bffa4-afad-49ac-b1bd-1c3883f89814)


![Screenshot 2023-09-11 at 3 18 35 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/84e39eba-69da-4ace-b7f0-a8347a6c125e)


### HOSPITALIZED CURRENTLY

![Screenshot 2023-09-11 at 3 19 16 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/bb86929b-a506-4302-8e0d-3b6ed7fe701e)

### DEATH

![Screenshot 2023-09-11 at 3 19 49 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/984071e3-1aab-4ca6-8426-2f5df8f9dd10)

## Analytical Approach
### Experiment 1
* A t-test was conducted to compare the total test results for the states of California (CA) and New York (NY)

### Experiment 2
* Regression analysis was conducted to check which key variables affect the total test results

## Experiment 1 Findings

* H0: There IS NOT a significant difference in the total test conducted in California and New York
* H1: There IS a significant difference in the total test conducted in California and New York

![Screenshot 2023-09-11 at 3 22 45 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/c512c4c6-ff7f-4c16-81bf-ab27e422f789)


## Experiment 2 Findings (California)
* H0: Death, Hospitalized currently and positive IS NOT a significant predictor of Total Test Results
* H1: Death, Hospitalized Currently And Positive IS a Significant Predictor Of Total Test Results
![Screenshot 2023-09-11 at 3 23 45 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/4237a09c-76e7-4ab0-bc2c-a94fca8bac6c)

## Experiment 2 Findings (New York)

* H0: Death, Hospitalized currently and positive IS NOT a significant predictor of Total Test Results
* H1: Death, Hospitalized Currently And Positive IS a Significant Predictor Of Total Test Results
![Screenshot 2023-09-11 at 3 24 51 AM](https://github.com/SparshChandra/Project_Covid19-effects-on-USA-States/assets/102770866/881a2a49-44b9-44cb-8f57-bca44af1ee3a)

## Interpretations

* As per the dataset, California had its first COVID-19 case a month before New York. By March, New York had eclipsed California, and cases exploded. Making challenges in both states.
* According to the results of experiment 1, which is the t-test done on the data set, there is a statistically significant difference between the total test conducted in California and New York.
* With regards to California-specific regression analysis, H1 was highlighted, indicating a significant predictor. Therefore, a review of the data set reveals that fatalities,
hospitalizations and the presence of positive outcomes are all important indicators for the state of California.
* While the statistical regression analysis conducted for the state of New York plainly indicates that there is no significant predictor in the data set that might provide insight into the increase in COVID occurring in the state, thus emphasizing the H0
