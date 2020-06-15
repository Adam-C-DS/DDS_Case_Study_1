# DDS_Case_Study_1 - Budweiser Presentation
## Carl and Adam's Case Study 1 Repo

###### Testing out my github syntax skills!

To be added:\
-Project Schedule\
-Project Details\
-EDA's\
-Relevant Statistical Outputs\
-Presentation Power Point

# NA Ideas
* Randomly generate data though rnorm based on company or style
* impute the average of the specific type of beer
  * This may cause issues for some of the analysis
* Change to a categorical variable based on scale: https://www.drtanknstein.com/2018/12/10/ibu-is-back/
* We can categorize on IBU and make the NA's a level and we can compare them separate if need be

# Where are the NA's for IBU?
* Need to gather beer by style to compare - Nix this there about 100 styles.
* Look at LM, KNN, and Naive Bayes to see which is best at predicting IBU and impute those values
* BeerBrewery Contains the original and factorized IBU
* BeerBreweryNA.delete has NA's deleted
* BeerBreweryNA.impute will have NA's Imputed
  * Then we can quickly run tests on all 3 to see which is best, or if it even matters

