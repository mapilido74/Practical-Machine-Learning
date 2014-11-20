# Synopsis

The goal of this project is *to predict* the manner in wich a group of enthusiasts did the exercise. For it we use data from accelerometers on the belt, forearm, arm and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. 

My strategy consists in building 2 models and compare them. This comparison will be centered on the accuracy level. The first model use the   *Principal Component Analysis* tool,  because some of predictors are highly correlated with each other. The second model use the subset of the training data , that in a previous step I splitted in two parts.

In both cases (models), I use the *random forest* technique, because is one of the accurate learning algorithms. Also I use *cross validation* as a type of resampling.
