# AB-Test

## Overview
This project is as assignment as part of the Data Analyst Nanodegree program by Udacity.
It analyzed the results of an A/B test run by an e-commerce website.
A hypothesis test is ran to see if the new web page should be implemented over the old page.
A regression model is applied to confirm the results of the hypothesis test.

### Installation
import all the necessary libraries

read in the dataset

`df=pd.read_csv('ab_data.csv')`

#### More Info on Sections
* Probability: Basic data wrangling done and finding the conversion rates between the control and expirement group.
* A/B Test: Perform hypothesis test with a Type 1 error rate of 5%.
* A Regression Approach: a statsmodel is used to fit the regression model.
