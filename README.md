# Logistic-Regression-Classification.
It is a predictive algorithm using independent variables to predict the dependent variable, just like Linear Regression, but with a difference that the dependent variable should be categorical variable.

Independent variables can be numeric or categorical variables, but the dependent variable will always be categorical

Logistic Regression can be used for binary classification or multi-class classification.

Binary classification is when we have two possible outcomes like a person is infected with COVID-19 or is not infected with COVID-19. In multi-class classification, we have multiple outcomes like the person may have the flu or an allergy, or cold or COVID-19.

Assumptions for Logistic Regression No outliers in the data. An outlier can be identified by analyzing the independent variables No correlation (multi-collinearity) between the independent variables.

Unlike linear regression which outputs continuous number values, logistic regression uses the logistic sigmoid function to transform its output to return a probability value which can then be mapped to two or more discrete classes.
In general, methods used to find the coefficients for the logistic function go through an iterative process of selecting a candidate line and calculating the log-likelihood. This is continued until the convergence is achieved and the maximum likelihood is found.
