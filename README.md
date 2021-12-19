# Neural_Network_Charity_Analysis
## Overview
Analyzing applicants to *Alphabet Soup* charity is a complex process that the business team would like to automate as much as possible.  Therefore, implementing some type of machine learning to help go through the thousands of applicants will help to not only identify the best possible candidates, but also to shorten the time it takes to evaluate all of the candidates.
## Results
### Data Preprocessing
A csv files of more than 34,000 organizations that have previously received funding from *Alphabet Soup* over the years was provided for this evaluation.  There were several data points that were not necessary for this analysis; EIN, Name, and the amount for which was previously requested and funded. 
We transformed some of the data from objects or strings to integers of 0 and 1.  This allows machine learning and neural networks to evaluate the data and do predictions.  

 - Target Variable: The target variable is the **IS_SUCCESSFUL** data.
 - Feature Variables: Basically, all other variables, but primarily any under the **APPLICATION_TYPE** data and **CLASSIFICATION** data, as well as **USE_CASE, AFFILIATION, and ORGANIZATION**.
 - Unnecessary Variables: **EIN, NAME, and ASK_AMT**. Also, we could potentially remove **SPECIAL_CONSIDERATIONS** and anything that was grouped in to an **Other** category. 

### Compiling, Training, and Evaluating the Model

 > Number of neurons, layers & activation functions: 
  - Neurons: Dense
  - Layers: 2
  - Activation Functions: RELU, RELU, & Sigmoid

## Summary
