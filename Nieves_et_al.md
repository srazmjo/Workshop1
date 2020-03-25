### Response to Nieves et al.
#### Sayyed Hadi Razmjo
#### March 25th

Question 1: Nieves et a. use the random forest machine learning method to predict what value globally?  Describe in detail how random forest works.  What is a dasymmetric population allocation? Which geospatial covariates proved to be the most important when predicting global values of where humans reside?

Answer: 

Random forests are non-parametric, nonlinear statistical methods that falls within a category of machine-learning methods known as ‘ensemble methods’. Ensemble methods take individual decision trees that are considered ‘weak learners’ and combine them to create a
‘strong learner’. The benefits of ensemble methods are that generalizability is increased, performance on large or small datasets is
improved and the ability of the method to model difficult learning tasks is more effective. Compared with other ensemble methods
RFs are robust to noise, small sample sizes and over-fitting, yet they need little in the way of parameter specifications. 
RFs independently generate k number of unpruned decision trees using ‘bagging’. Once a decision tree is grown, the
one-third of the bagged training data that the tree was not grown upon remain and are known as the ‘out-of-bag’ (OOB)
data. The decision tree applied to these data and the accuracy of the tree, as measured by the mean squared error (m.s.e.), are
stored as the OOB error for that tree. Then the prediction error of entire RF model can be measure by averaging the OOB errors of all trees.

Dasymetric modelling has evolved significantly over the past few years and provided important insights into the relationships between population and ancillary variables. Such analyses have the potential to uncover fundamental patterns in the correlates and drivers of population distributions across the world. Dasymetric mapping is a method that is used to estimate a population layer from input census and covariate data. The general steps are as follows: 
1. Iterative covariate selection for the RF model 
2. The fitting of the RF model, using all available census units, and creation of a population density weighting layer from the created RF model
3. The dasymetric redistribution of population counts from census-based administrative units to grid cells [29] using the population density weighting layer. 

The consistent patterns of covariate importance to predicting population density were observed between all sampled countries globally, with similar patterns observed between regions of countries. The correlates pertaining to urban areas and, more surprisingly, topographical features, built enviornments, urban/suburban proxies, enviornmental variables, and populated place covariates were the most important predictors of global values of where humans reside at all scales of analysis and were the only covariate categories which were consistently significantly more important than other categories.

