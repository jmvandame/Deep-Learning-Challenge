# Deep-Learning-Challenge
Module 21


1. Overview of the analysis: 

    The nonprofit foundation Alphabet Soup is seeking help to select applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, I have used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The target goal of 75% accuracy for our model. From Alphabet Soup’s business team, I received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

    EIN and NAME—Identification columns
    APPLICATION_TYPE—Alphabet Soup application type
    AFFILIATION—Affiliated sector of industry
    CLASSIFICATION—Government organization classification
    USE_CASE—Use case for funding
    ORGANIZATION—Organization type
    STATUS—Active status
    INCOME_AMT—Income classification
    SPECIAL_CONSIDERATIONS—Special consideration for application
    ASK_AMT—Funding amount requested
    IS_SUCCESSFUL—Was the money used effectively

2. Results: Using bulleted lists and images to support your answers, address the following questions:

    Data Preprocessing

What variable(s) are the target(s) for your model?

Target Variable for the model:

IS_SUCCESSFUL

What variable(s) are the features for your model?

Feature Variables for the model:

APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT

What variable(s) should be removed from the input data because they are neither targets nor features? I removed ORGANIZATION from the data set in an attempt to optimize results. 

    Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance? While model optimization increased from 72.5% to 72.8% I did not reach the target of 75% after applying three optimization techniques. 

What steps did you take in your attempts to increase model performance? In an effort to increase model performance I removed the ORGANIZATION column, added additional neurons, and added additional hidden layer. 


Recommendation: Perform the model using automatic tools to perform optimitzation on the model and provide a larger data set. 