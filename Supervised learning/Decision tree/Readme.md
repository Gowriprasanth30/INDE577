
# What is decision Tree?

 Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.
For instance, in the example below, decision trees learn from data to approximate a sine curve with a set of if-then-else decision rules. The deeper the tree, the more complex the decision rules and the fitter the model.
Some advantages of decision trees are:
•	Simple to understand and to interpret. Trees can be visualised.
•	Requires little data preparation. Other techniques often require data normalisation, dummy variables need to be created and blank values to be removed. Note however that this module does not support missing values.
The disadvantages of decision trees include:
•	Decision-tree learners can create over-complex trees that do not generalise the data well. This is called overfitting. Mechanisms such as pruning, setting the minimum number of samples required at a leaf node or setting the maximum depth of the tree are necessary to avoid this problem.
•	Decision trees can be unstable because small variations in the data might result in a completely different tree being generated. This problem is mitigated by using decision trees within an ensemble.


## Dataset used and task

We are using daily_weather.csv from Kaggle
In this notebook we implement the decision tree algorithm for indicating whether it is humid or not based on features such as ['air_pressure_9am', 'air_temp_9am', 'avg_wind_direction_9am', 'avg_wind_speed_9am', 'max_wind_direction_9am', 'max_wind_speed_9am', 'rain_accumulation_9am', 'rain_duration_9am', 'relative_humidity_9am']
Using these features we are predicting 'relative_humidity_3pm'

## Libraries used
Libraires:
Pandas https://pandas.pydata.org/

Matplotlib https://matplotlib.org/

Numpy https://numpy.org/

Seaborn https://seaborn.pydata.org/

Scikit-learn https://scikit-learn.org/