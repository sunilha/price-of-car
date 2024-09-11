# price-of-used-car
What drives the price of a used car?

## Project Overview
The goal of this project is to understand what factors make a car more or less expensive. 
Here we are going to explore a subset of a dataset from kaggle.

## Findings Summary
After all the analysis and modelling found the below top features has impact on car price. All the linear regression models employed resulted with same features. These observations resonates with real world expectations.

- Condition (State of the car)
- Year (Age of the car)
- Type (Car segment)
- Manufacturer (Brand matters)

Further analysis and modelling only this top features using ridge model, found R2 score close to zero i.e. there is no linear relationship with individual features. This observation convey that there are multiple features affecting the car price not just one.

Car dealership should incorporate these findings when filling their inventories to get better price for the used car. 

Jupyter Notebook having code for all these can be found [here](Solution.ipynb) and the consolidated answers of each CRISP-DM phase can be found [here](what-drives-car-price.ipynb).
