# ML NYC Property Data Analysis
Final Project for CS-UY 4563 - Introduction to Machine Learning using NYC Property Sales dataset from https://www.kaggle.com/new-york-city/nyc-property-sales/activity

Properties:
* Borough 
* Block
* Lot
* Commerical Units
* Land Square Feet
* Gross Square Feet
* Sale Price
* Year Built
* Tax Class at time of sale 

Process:
1. Clean up data that did not make sense
2. Pre-process data using scaling and min/max normalization
3. Run linear regression
4. Perform feature transformation + run learning Methods
5. Add regularization + run learning method

Learning Methods
* Multiple Linear Regression
    * Features: Block, Lot, Commerical Units, Land Square Feet, Gross Square Feet, Year Built, Tax Class at time of sale
    * Target: Sale Price
* Logistic Regression
    * Features: Block, Lot, Commerical Units, Land Square Feet, Gross Square Feet, Sale Price, Year Built, Tax Class at time of sale
    * Target: Borough: Brooklyn or Queens
* SVM
    Same as Logistic?
    * Features: 
    * Target: 