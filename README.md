# Wind-Power-Output-Predictor
This is a simple regressor which is trained on telemetry from a bunch of wind turbines from several different locations. 
It takes environmental factors such as temperature, wind speeds at different altitudes, wind direction at different altitudes, etc as input & predicts the percentage of the turbine output compared to it's full capacity.

The data was pulled from [this Kaggle page](https://www.kaggle.com/datasets/mubashirrahim/wind-power-generation-data-forecasting).

The project contains the following models trained on the dataset:
  - Decision tree
  - Random forest
  - Linear regression
  - Gradient boost
  - XG Boost

I have chosen multiple metrics to compare all the models, they are as follows:
  - Mean absolute error
  - Root mean squared error
  - R<sup>2</sup>
  - Adjusted R<sup>2</sup>

They're visually plotted on graphs corresponding to their scales (R squared & Adj R squared are converted into percentages)

<sub>_Note: Can you guess the colour theme of the graphs?_</sub>
