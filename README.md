# Wine Quality Classification
![myimage-alt-tag](https://ak.picdn.net/shutterstock/videos/25618235/thumb/8.jpg)

## Description 
####
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

##  PROBLEM STATEMENT
 To build various classification models to predict whether a particular red wine is “good quality” or not. Each wine in this dataset is given a “quality” score between 0 and 10. For the purpose of this project, I converted the output to a binary output where each wine is either “good quality” (a score of 7 or higher) or not (a score below 7). The quality of a wine is determined by 11 input variables.

## ALGORITHMS USED
KNN, Decision Tree


## ACCURACY ON TRAINING AND TESTING RESPECTIVELY
* 96%
* 89%

![Wine-Glass-720x450](https://user-images.githubusercontent.com/47673623/93524363-06816800-f952-11ea-867b-897651079501.jpg)


## DATASET INFORMATION 

 * COLUMNS :-
   *  Fixed acidity

   *  Volatile acidity

   *  Citric acid

   *  Residual sugar

   *  Chlorides

   *  Free Sulfur-Dioxide
 
   *  Total Sulfur-Dioxide

   *  Density

   *  pH

   *  Sulphates

   *  Alcohol
 
Output variable (based on sensory data):

* quality (score between 0 and 10)
  
## DETAILED DESCRIPTION OF IMPORTANT FEATURES


* Fixed acidity

  Most acids involved with wine or fixed or nonvolatile (do not evaporate readily).
 
* Volatile acidity

  The amount of acetic acid in wine, which at too high of levels can lead to an 
  unpleasant, vinegar taste.

* Citric acid

  Found in small quantities, citric acid can add 'freshness' and flavor to wines.

* Residual sugar
  
  The amount of sugar remaining after fermentation stops, it's rare to find wines 
  with less than 1 gram/liter.

* Chlorides

  The amount of salt in the wine .
