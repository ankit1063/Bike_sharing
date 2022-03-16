# Project Name
> Bike Sharing Assignment Multiple linear Regression


## Table of Contents
* [About](#About)
* [Technologies Used](#technologies-used)
* [Data analysis](#dataanalysis)
* [Univariate](#univariate)
* [Bivariate](#bivariate)
* [Encoding](#encoding)
* [Normalisation](#normalisation)
* [Modelling and prediction](#model)
* [Residual analysis and Feature analysis](#Feature analysis)
* [Contact](#Contact)


<!-- You can include any other section that is pertinent to your problem -->

## About
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## technologies-used
- Python
- Numpy
- Matplotlib
- Seaborn
- Pandas
- Sklearn
- Statsmodel

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## dataanalysis
- Well preformed data analysis in given data set with almost 16 different columns
- got informtaion regading categorical and numerical columns
- checked with null values
- checked with dropping not use ful columns
- 

## univariate
- in univariate analysis checked with the analysis of the cnt with different types
- of data with categorical and numerical data by plotting grapsh using seaborn


## bivariate
- in bivariate analysis checked with the analysis heat may tried to find the correlation of different 
- variables


## encoding
-  directly went with one hot encording as there was less number of categorical variables
- tried to used drop = true feature on also to reduce the eccoding variable in each category

## normalisation
-tried to convert the whole data on normalised format so that every point in our data should have 
value between 0 am 1 
## model
-tried to implemet the multile linear regesssion model with inital step of addign constant and 
procceding forward rteid to incease model accuracy by hit an trial method many time in first  time
than predicting the model using R2 score on both test and train

## Feature analysis
-once done with hit and trial method tried to use Recursive feature analysis which give me the top 10 best 
feature and also checked with the VIF values than than tried to fidn the Residual analysis
using test and train data

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@ankit1063] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->