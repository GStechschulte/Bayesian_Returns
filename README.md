# Bayesian_Modeling-Funds

- **Motivation**:
    - Investments with high returns are desirable. In regard to stocks, using the historical dataset is unwise as the parameter of interest is subject to change
        - Parameter(s) of interest include:
            - 1.) Mean monthly return, 2.) Monthly standard deviation
    - So why not use a smaller dataset? 
        - A smaller sample size produces greater uncertainty for the parameter(s) of interest
- **Objective**:
    - Insert domain knowledge into our prior probability of the model
    - This will allow us to reduce the use of past data, and to put an emphasis on our prior probability
        - As we gain more evidence, our prior probability is "washed out" by the new instances 
            - After observing the new evidence, our belief is updated; which is called the posterior probability
            - __“Today's posterior is tomorrow's prior”__
    - In Bayesian Inference, we have access to the parameters posterior distribution which will allow us to interpret point and interval estimates
