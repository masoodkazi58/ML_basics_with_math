# linear Regression
### 1.Simple Linear Regression
Simple linear regression s a statistical method used to model the relationship between two continuous variables: 
an independent variable (predictor) and a dependent variable (response). 
The goal is to find a straight line that best fits the data points, allowing us to predict the value of the dependent variable based on the independent variable.

#### Y = b0 + b1X
- x is Independent Variable, Plotted along X-axis.
- y is Dependent Variable, Plotted along Y-axis
- B0 is a Constant
-B1 is Regression Coefficient
  Here, B1 is the regression coefficient and its formula is,

#### B1 = b1 = Σ [ (xi – x)(yi – y) ] / Σ [(xi – x)2]
- where,
- xi and yi are Observed Data Sets
- x and y are Mean Value
#### summary
- the data where training is placement data of a college.it includes 2 columns "cgpa" and "package'
- using scikit learn Machine learning library we need train the "cgpa" and "package" column and predict the package
- i have imported train_test_split module "X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=2)".
  where test_size is 20% that means we are training 80% of data.
###### after training and predicting the data with inbuilt library I have built the exact model from scratch with mathematical logic 

#### Tools
- jupyter notebook
- Scikit learning ibrary
- seabon for visualization
- pandas and numpy


