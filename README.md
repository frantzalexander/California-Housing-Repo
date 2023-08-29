# California Housing Price Analysis


## Project Overview
This analysis will use linear regression to predict housing prices based on neighbourhood housing prices in California.


## Objectives
- Build a Linear Regression Model to predict housing prices.
- Evaluate the dataset features for use in the model.
- Determine the feature importances.

## Results
- The Training Mean Absolute Error: 52050.32
- The Test Mean Absolute Error: 54180.78
- The most valuable neighborhoods were in cities especially along the coastline.
- The highest concentrations of houses were in neighborhoods with fewer than 3000 rooms and below median values of $300,000.
- The most important features for determining the neighborhood value in order of importance:
    1. Location
    2. Median Age
    3. Number of rooms
    4. Distance to the coastline.
    
- A linear regression model was not the correct model for this dataset.
- The house price distribution was bimodal.
- This indicates that the model would be influenced by two groups with different characteristics.
   
## Process
```mermaid
flowchart TD
start(((START)))
prepare[Data Preparation]
import[Import Data]
explore[Data Exploration]
train[Train-Test Split]
model[Model Building]
baseline[Create Baseline Model]
iterate[Iterate]
evaluate[Model Evaluation]
communication[Communication]
key[Key Insights]
finish(((END)))

start --> prepare
prepare --> import
import --> explore
explore --> train
train --> model
model --> baseline
baseline --> iterate
iterate --> evaluate
evaluate --> communication
communication --> key
key --> finish
