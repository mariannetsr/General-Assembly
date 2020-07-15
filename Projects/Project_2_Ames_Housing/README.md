# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Sale Price Prediction

<img src="./assets/graphics/Ames.jpg">


## Executive Summary

In this project, we dived into an exceptionally detailed and robust housing dataset from the city of Ames in Iowa, USA.

After the initial phase of EDA and cleaning, we fitted various models to the housing data to determine features that are most/least influential to housing prices.

After which, our predictions were submitted to [Kaggle](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/submit) to see how our model does against unknown data.

Lastly, the project ends off with findings and recommendations from our models.

Due to the length of the project, I've split the Jupyter notebooks into two:
1. EDA & Cleaning 
2. Predictive Modeling

---

## Problem Statement

["Location, location, location."](https://www.thebalance.com/what-location-means-in-real-estate-1798766) We've heard this mantra countless times when talking to a real estate agent about home values. In a nutshell, it means homes can vary widely in value due to their location. However, are there other features and metrics that we can look at to predict home values? Homeowners looking to increase the value of their homes often spend too much on remodelling and don't get the return of investment they're expecting when selling the house.

As such, we want to predict the saleprice for houses in Ames:
- Apart from the location, what features add the most value to the house, and which hurt the value the most?
- As a homeowner, is there anything you can do to your house to increase your sale price?

---

## Dataset 

Dataset contains information from the Ames Assessor’s Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010. Source: Ames, Iowa Assessor’s Office. Full description can be found in the data documentation [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

---

## Summary & Recommendations

#### Location
The phrase ["location, location, location"](https://www.thebalance.com/what-location-means-in-real-estate-1798766) is still valid when it comes to property. Neighborhoods do play a part in the price of a house. In Ames, the most desirable neighbourhoods appear to be: 
- Northridge Heights: located in the Gilbert School District and close to Ada Hayden Lake and recreation area, Somerset Village restaurants and shopping, and North Grand Mall
- Stone Brook: 5 minute drive to Iowa State University, preferred neighborhood for students and faculty staff
- Northridge: situated close to three public schools, Somerset Village restaurants and shopping and North Grand Mall 

However, location is not all of it and there are other features that add value to a home.

#### House Type
- Top features: Above ground living area, newer houses, overall quality and condition. These are expected but is there more? 

- Basement score: This was an engineered feature where we combined all the different features of the basement e.g. quality, condition, exposure, rating of the basement. To raise home sale prices, homeowners can consider upgrading their basements.

- Surprising features: Garage and fireplaces. Upon doing some research, the reason for why fireplace(s) is an important feature in a house could be because [Iowa has one of the worst winters in the US](https://khak.com/iowa-ranked-among-states-with-most-miserable-winters/).

- Features to avoid: Townhouses and too many bed rooms. Although price genearally increases with the size of the house, it is negatively correlated with the number of bedrooms.

#### Can this model be generalized with other cities?
- As Ames is a college town where [half of its population are studens from Iowa State University](https://en.wikipedia.org/wiki/Ames,_Iowa), our model might only generalise well to similar [college towns in the US](https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States).
- The dataset we've used for this model is collected between 2006-2010 which coincides with the [subprime mortgage crisis](https://en.wikipedia.org/wiki/Subprime_mortgage_crisis). There was a large decline in housing prices which means that the data may not generalise well to other periods of time. 

