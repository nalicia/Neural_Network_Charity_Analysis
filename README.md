# Neural Networks
## Overview
For our final project we were tasked with making an acurate and concise neural network model using tensor flow and deep learning neural networks. 
The goal of the project was predicting if applicants would get funding from AlphabetSoup based on the succession of the charity applying. 
## Fisrt steps in the data proccessing 
* Gathering the unique values
* Encoding categorical variables with hot encoding
* Splitting the data into features and targets
* Splitting the data into training and testing sets 
* Using Standard scaler to evaluate the standardized numerical values

## Results
### Data Preproccessing 
In order to clean the data we removed "Ein" and the  "NAME" Columns because they added no statstcial value to the data
The feauture variables include: "STATUS", "ASK_AMT", "APPLICATION_TYPE", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT".
I  dropped the colunmns including the word "other" as they pertain to the outliers in this scenario. 
Our dependent variable is "IS_SUCCESSFUL" as our predictor. 
### Evaluating the model
There were 2 hidden layers, 80 neurons in the first layer and 30 neurons in the second layer.
I was not able to achieve the target model performance because I could not get tensor flow to work in Jupyter. I tried several techniques, including unintsalling and downloading, termional commands, and even uploading the data into Google Colab to see if I could getit running there, all with no luck. 

## Summary
Building and training machiene learning models is crucial in the analytics world. Many buisnesses use the predictive index to make decisions that could make or break their buisness. Unfortunatly I was not able to get it working in VS code/ Jupyter notebook. I will be coming back to this project at a later date. 
