# deep-learning-challenge

-----
# Neural Network Model Report

## Overview 
This analysis aims to construct a binary classifier employing machine learning and neural networks. Its objective is to forecast the likelihood of success for applicants seeking funding from the nonprofit organization Alphabet Soup. The intent is to create a tool to aid the business team in identifying applicants with the highest potential for success in their endeavors, leveraging the provided dataset.

-----
## Results

### Data Preprocessing
* The target variable for this model is the IS_SUCCESSFUL column of the dataset, which indicates if the money was used effectively.
* Feature variables:
  * APPLICATION_TYPE — Alphabet Soup application type
  * AFFILIATION — Affiliated sector of industry
  * CLASSIFICATION — Government organization classification
  * USE_CASE — Use case for funding
  * ORGANIZATION — Organization type
  * STATUS — Active status
  * INCOME_AMT — Income classification
  * SPECIAL_CONSIDERATIONS — Special considerations for application
  * ASK_AMT — Funding amount requested
* The variables that were removed because they were neither targets nor features were the EIN and NAME columns.


### Compiling, Training, and Evaluating the Model
* Model 1
  * In my first model, I opted for 80 neurons in the first hidden layer and 30 neurons in the second hidden layer and employing the ReLU activation function for both hidden layers, the   objective was to devise a model with ample complexity to grasp and comprehend significant patterns within the dataset. The selection of ReLU activation facilitates the introduction     of non-linearity, enabling the model to discern intricate relationships between the input features and the target variable.

<img width="748" alt="Screenshot 2024-03-06 at 12 52 10 PM" src="https://github.com/brianne-han/deep-learning-challenge/assets/142977736/9ee59c1d-4748-468e-b270-82a0bb278296">

  * I only achieved 72.6% accuracy, which is not the target model performance of 75%.
    
<img width="504" alt="Screenshot 2024-03-06 at 12 54 31 PM" src="https://github.com/brianne-han/deep-learning-challenge/assets/142977736/c9b51534-931d-4f64-bbe5-6e2f73d3c159">

    
-----

## Summary
