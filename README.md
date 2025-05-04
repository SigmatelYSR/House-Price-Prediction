# House-Price-Prediction
Housing prices reflect economic trends and matter to buyers and sellers. A home's value goes beyond location and size—many factors shape its worth. Sellers estimate prices by comparing similar properties nearby. This study aims to predict housing prices based on local features and identify key factors that influence valuation.
## Context
Housing prices are an important reflection of the economy, and housing price ranges are of great interest for both buyers and sellers. Ask a home buyer to describe their dream house, and they
probably won’t begin with the height of the basement ceiling or the proximity to an east-west railroad. A house value is simply more than location and square footage. Like the features that make
up a person, an educated party would want to know all aspects that give a house its value. For example, you want to sell a house and you don’t know the price which you may expect—it can’t be
too low or too high. To find house price you usually try to find similar properties in your neighborhood and based on gathered data you will try to assess your house price.
## Objective
The objective of this problem statement is to predict the housing prices of a town or a suburb based on the features of the locality provided and identify the most important features to consider while
predicting the prices.
##Data Dictionary
This dataset has 23 features, price being the target variable. The details of all the features are given below:
- cid: a notation for a house
- dayhours: Date house was sold
- price: Price is prediction target (in $)
- room_bed: Number of Bedrooms per house
- room_bath: Number of bathrooms per bedrooms
- living_measure: square footage of the home
- lot_measure: square footage of the lot
- ceil: Total floors (levels) in house
- coast: House which has a view to a waterfront (0 - No, 1 - Yes)
- sight: Has been viewed
- condition: How good the condition is (Overall out of 5)
- quality: grade given to the housing unit, based on grading system
- ceil_measure: square footage of house apart from basement
- basement_measure: square footage of the basement
- yr_built: Built Year
- yr_renovated: Year when house was renovated
- zipcode: zip code
- lat: Latitude coordinate
- long: Longitude coordinate
- living_measure15: Living room area in 2015 (implies-- some renovations) This might or might not have affected the lot size area
- lot_measure15: lotSize area in 2015 (implies-- some renovations)
- furnished: Based on the quality of room (0 - No, 1 - Yes)
- total_area: Measure of both living and lot
