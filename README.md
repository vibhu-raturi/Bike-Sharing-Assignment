#  Bike Sharing Assignment
>  A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free.
> It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technical Stacks](#technical-stacks)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-  Business Problem : The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand   how exactly the demands vary with different features. 
- Objective : Create a linear model that describe the effect of various features on demand. The model should be interpretable so that the management can understand it.
- Dataset : Dataset used here for this assignment is 'day.csv'.
- We also have a Data Dictionary for our refrence and understanding of the variables used in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-  We were able to build a Linear Regression Model for this Bike Sharing assignment
- Linear Model 6 is significant with all p-Values and VIF values below the threshold as per industry standards. We can the script using Bike Sharing Linear Regression.ipynb for all the details.
- 'temp', 'Light Rain/Snow & Scattered Clouds' & 'year' are the top three variables which contribute significantly towards the target variable 'count' which is the count of Bike Sharing. We can check the linear equation in the python script mentioned earlier.
- Assumpitions in Linear Regression such as Normal Distribution in error terms, Homoscedasticity, Multicollinearity(VIF) are checked during Model Building and were True.
- Difference between R-Squared & Adjusted R-Squared for train and test data was not above 5%  and were close to each other as well. Which implies No Overfitting and the model is working fine with test data as well.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technical Stacks
- Python
- Jupyter Notebook
- Git Bash

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@vibhu-raturi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
