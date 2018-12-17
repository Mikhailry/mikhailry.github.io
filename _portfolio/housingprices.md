---
title: "Predicting Housing Prices"
excerpt: "Predicting housing prices in CHICAGO, considering house facts, crime rates, socioeconomic conditions, school ratings and proximity to CTA"
header:
  #image: /assets/images/housingprices/map_mean.png
  teaser: assets/images/housingprices/map_mean-th.png
sidebar:
  - title: "Responsibilities"
    #image: /assets/images/housingprices/logo.png
    #image_alt: "logo"
    text: "Data wrangling, visualizations, linear models"
gallery:
  - url: /assets/images/housingprices/map_mean.png
    image_path: assets/images/housingprices/map_mean-th.png
    alt: "map of community mean prices"
  - url: /assets/images/housingprices/map_crime.png
    image_path: assets/images/housingprices/map_crime-th.png
    alt: "map of communities crime rates"
  - url: /assets/images/housingprices/map_schools.png
    image_path: assets/images/housingprices/map_schools-th.png
    alt: "map of communities school ratings"
---

## Abstract
In this project, price of houses in Chicago, Illinois region are predicted. First, data
pertaining to specific characteristics of the house is gathered. This is combined with
data from other sources, such as, socioeconomic conditions of the regions, crime-rates
in different localities and distance from nearest CTA ’L’ station. Exploratory analysis
is then performed to identify trends, correlation and derive other interesting insights
from the data. Following this, machine learning models are built to accurately predict
the price of a house, and the performance of the models are measured. Model selection
is performed based on the performance metric to identify the best performing model
and validate the accuracy of the predictions on new data. We conclude that tree-based
XGBoost model predicts the house price most accurately. We also observe some
important predictor variables, including square footage of the house, the number of
baths in the house and the socio-economic condition of the communities.


{% include gallery caption="Examples of interactive map with summary metrics." %}


[If you are interested in more details, please refer to a full report](https://github.com/Mikhailry/HousingPrice/blob/master/report/HousingPriceProject.pdf)

[Repository](https://github.com/Mikhailry/HousingPrice)

[The interactive map of Chicago communities with the variety of summary metrics about the houses for sale overlayed]()
