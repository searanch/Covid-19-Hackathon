# Machine Learning for Social Good: COVID-19

## Problem Statement
To date in the United States, COVID-19 has infected 5.2+ million people, killing over 165 thousand. The Midwest has not yet seen the spike in cases that the Southern and Western Regions of the country have. Winter Is Coming & Midwesterners won’t have as many options to congregate outdoors.

Can we predict when the Midwest will see spikes in order to better prepare, knowing that people moving indoors will likely lead to more cases?

## Our Solution

We used the Enigma dataset from [AWS Data Exchange](https://us-east-2.console.aws.amazon.com/dataexchange/home?region=us-east-2#/subscriptions/prod-w6zhufgnqkyiu).  We selected just the states in the West Northern Central Region to use for our predictions.  

While exploring our data, we calculated the growth rate of cases and graphed it to see how it has changed over time.
![Growth Rate Graph](/readme_images/growth_rate.png)

We then made predictions using Linear Regression on cases for some important upcoming dates: Labor Day, Elections Day, Thanksgiving, and Christmas. Predictions were made for the region as a whole as well as each of the 6 states in the region.

![Cases and Predictions](/readme_images/cases_and_predictions.png)

## Moving Forward

For continued analysis, we would like to incorporate other states and countries to try to get a bigger picture.  We would like to include other features for prediction like ventilator use and ICU hospitalization.  It would also be beneficial to pull in Census data to control for population.


## Packages Used
* Sklearn
* Pandas
* Matplotlib
* Numpy