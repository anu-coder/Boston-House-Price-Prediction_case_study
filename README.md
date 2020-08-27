# Boston House Prices Prediction: A case study
**Solo project: by Anurima Dey** 
 
 ## Purpose:
 
I started my journey of understanding the machine learning algorithms using this project. In the confusion of which topic to choose, "clssification!", "regression?", "classification??", "regression!!", I thought why not start with the topic whose starting alphabet has a higher ASCII value, which is "R", i.e. regression....(Kudos to Random logic :'D). Well but the main purpose was to understand a regression problem (i.e  when we are predicting a continuous variable) and applying machine learning techniques to obtain the objective i.e. a decent accuracy. The continuous variable here is the MEDV (median value of the owner occupied homes). This BHPP is also a beginners project to deploy a data analyst career, as enlisted by Kaggle. 

## Objective: 

Let be precise: 
1. Obtaining and cleaning the data.
2. Data Exploration through data Visualization, popularly termed as Exploratory Data Analysis (EDA).
3. Optimal and necessary Feature Selection and data partitioning (Train and Test)
4. Fitting various regression models, and Random Forest model with grid search, and cross validation. 
5. Have also applied PCA to check if it increses accuracy. 
6. The error matrices used to check the accuracy was RMSE, MAPE, MAE, MSE. 
7. Tried to create self help plotting packages available in [R_utils repository](https://github.com/anu-coder/R_utils)

## Some visulization for the dataset: 

The dataset is obtained from Kaggle stored in [here](https://github.com/anu-coder/R_utils/tree/master/R)

**The Description of the dataset:**

<p align = "left">
<img height = 250, width = 600, src = "https://github.com/anu-coder/Boston-House-Price-Prediction_case_study/blob/master/Images/1.PNG">
</p>

**The Histogram of MEDV**

<p align = "left">
<img height = 250, width = 500, src = "https://github.com/anu-coder/Boston-House-Price-Prediction_case_study/blob/master/Images/2.PNG">
</p>

**Correlation between various attributes**

<p align = "left">
<img height = 250, width = 500, src = "https://github.com/anu-coder/Boston-House-Price-Prediction_case_study/blob/master/Images/3.PNG">
</p>

## Procedure: 

I have mainly deployed the problem using three different linear regression models with repeated cross validation for model training. 

#### Model 1:

$MEDV= \alpha + \beta X + \epsilon$  where </br>
$X$: the matrix containing all the independent variables, </br> 
$Y$: the dependant variable MEDV. </br>
$\epsilon$ : residual error.

#### Model 2:

$log(MEDV)= \alpha+ \beta X + \epsilon$

#### Model 3:

$log(MEDV)=\alpha+\beta X+\epsilon, where \ X \ is \ a \ matrix \ of \ ~ DIS+RAD+LSTAT+NOX+INDUS+CRIM+TAX $




