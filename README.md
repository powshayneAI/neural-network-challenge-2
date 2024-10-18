# neural-network-challenge-2

## Project Overview
This project implements a neural network model with dual output branches to predict employee 'Attrition' and 'Department' classifications. The model architecture features separate hidden and output layers for each prediction task.
Data Processing Steps

## Preprocessing

Cleaned and organized raw employee data
Handled missing values
Removed outliers where appropriate


## Scaling

Applied feature scaling to normalize numerical variables
Ensured all features are on comparable scales for optimal model performance


## Encoding

Performed one-hot encoding for categorical variables
Encoded target variables ('Attrition' and 'Department') appropriately



## Model Architecture
The neural network consists of two branches:

### Branch 1 - Attrition Prediction

Input Layer → Common Features
Hidden Layer → Dense layer with ReLU activation
Output Layer → Binary classification for Attrition

### Branch 2 - Department Prediction

Input Layer → Common Features
Hidden Layer → Dense layer with ReLU activation
Output Layer → Multi-class classification for Department

## Model Training and Evaluation

Split data into training and testing sets
Compiled model with appropriate loss functions for each branch
Trained model using batch processing
Evaluated prediction accuracy for both Attrition and Department

## Summary
Once everything is completed, three questions will be answered in the summary portion of the file.
1) Is accuracy the best metric to use on this data? Why or why not?
2) What activation functions were chosen for output layers, and why?
3) Can you name a few ways that this model could be improved?