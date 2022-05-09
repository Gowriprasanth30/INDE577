
##  Logistic Regression


In statistics, the logistic model (or logit model) is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead or healthy/sick. This can be extended to model several classes of events such as determining whether an image contains a cat, dog, lion, etc. Each object being detected in the image would be assigned a probability between 0 and 1, with a sum of one.
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression[1] (or logit regression) is estimating the parameters of a logistic model (a form of binary regression). Mathematically, a binary logistic model has a dependent variable with two possible values, such as pass/fail which is represented by an indicator variable, where the two values are labeled "0" and "1". In the logistic model, the log-odds (the logarithm of the odds) for the value labeled "1" is a linear combination of one or more independent variables ("predictors"); the independent variables can each be a binary variable (two classes, coded by an indicator variable) or a continuous variable (any real value). The corresponding probability of the value labeled "1" can vary between 0 (certainly the value "0") and 1 (certainly the value "1"), hence the labeling; the function that converts log-odds to probability is the logistic function, hence the name. The unit of measurement for the log-odds scale is called a logit, from logistic unit, hence the alternative names.


##  Dataset Used

Random data set from kaggle. Using this data set we are trying to find type of species using our input features.
##  Task
This is multi-input logistis regression model where we are estimating the type of species using input parameters such as

LongestShell

Diameter

Height

WholeWeight

ShuckedWeight

VisceraWeight

ShellWeight

Rings

And our output is Type.
##  Libraries Used

Pandas https://pandas.pydata.org/

Matplotlib https://matplotlib.org/

Numpy https://numpy.org/

Seaborn https://seaborn.pydata.org/

Scikit-learn https://scikit-learn.org/