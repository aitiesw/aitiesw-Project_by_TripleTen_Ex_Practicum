
# Oil Well Model

You work for the OilyGiant mining company. Your task is to find the best place for a new well.
Steps to choose the location:
- Collect the oil well parameters in the selected region: oil quality and volume of reserves;
- Build a model for predicting the volume of reserves in the new wells;
- Pick the oil wells with the highest estimated values;
- Pick the region with the highest total profit for the selected oil wells.
You have data on oil samples from three regions. Parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.


## Data:

`geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`:

- *id* — unique oil well identifier
- *f0, f1, f2* — three features of points (their specific meaning is unimportant, but the features themselves are significant)
- *product* — volume of reserves in the oil well (thousand barrels).

## Goal:

1. Developing a model using the provided data on each oil well region
2. Creating an algorithm that calculates the volume of reserves sufficient for developing a new well without losses
3. Writing a function to calculate net revenue generated using selected oil wells and model predictions as parameters
4. Calculating risks and profit for each oil well region.


