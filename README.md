
### Domain of the Problem :
Sources: 
(a) Origin: This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. 
(b) Creator: Harrison, D. and Rubinfeld, D.L. 'Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978. 

### Problem Statement: 

The main purpose of this study is to prepare the data for a full analysis. The goal is to condition the data in preparation for analysis and model building, and to make clear the reasoning behind the decisions made in the preparation of the data.

### Description of Data Set:

The Housing data set consists of 14 attributes and 506 instances.The data set consists of 7084 data points occupying 54.7 kB of memory. There are no missing values, and no duplicate rows.

1. CRIM      per capita crime rate by town
2. ZN        proportion of residential land zoned for lots over 
             25,000 sq.ft.
3. INDUS     proportion of non-retail business acres per town
4. CHAS      Charles River dummy variable (= 1 if tract bounds 
             river; 0 otherwise)
5. NOX       nitric oxides concentration (parts per 10 million)
6. RM        average number of rooms per dwelling
7. AGE       proportion of owner-occupied units built prior to 1940
8. DIS       weighted distances to five Boston employment centres
9. RAD       index of accessibility to radial highways
10. TAX      full-value property-tax rate per $10,000
11. PTRATIO  pupil-teacher ratio by town
12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
             by town
13. LSTAT    % lower status of the population
14. MEDV     Median value of owner-occupied homes in $1000's

Number of Instances: 506

### Proposed Solution

A good solution would be multiple linear regression. We could perform some feature engineering to see if creating new features from the exsiting ones would help improve a model's predictive power. A multiple linear regression using all the features would allow us to identify which are most significant, and should be retained, and which can be dropped. 

### Benchmark Model

A good naive model would be simple linear regression. Some of the data plots we created indicate a linear relationship might exist between variables and the target.

### Performance Metrics: Accuracy

We can assess accuracy using the multiple R-square and the F-statistic using linear regression model. Using a multiple linear regression model, we could assess accuracy using the residual standard error and the R-squared.