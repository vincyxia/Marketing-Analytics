# MSBA Marketing Analytics Final Project - Customer Targeting Analysis

## Project requirement

**Goal** : working on real marketing data and going through the challenges faced in marketing analytics.

1. Define the problem and get the data
2. Conduct the data analysis
3. Present the results

## Project description

Our project is about customer targeting. We want to know how customer demographics influence customer purchasing behavior.

We faced several questions:

1. Highly imbalanced dataset
2. Model choose
3. Variable selection

We solved these questions by:

1. Using several sampling methods, including under-sampling method, random over-sampling method and SMOTE+ENN, to generate a reasonably balanced dataset. We utilized AUC as metric to choose proper sampling method and we chose SMOTE+ENN.

2. We used logistic regression model to build model because the result of logistic regression model is easy to interpret. As our goal is to find which customer to target, we need the model result to be interpretable.

3. We tried dummy variables, interaction variables, non-linear transformation to select proper variables.