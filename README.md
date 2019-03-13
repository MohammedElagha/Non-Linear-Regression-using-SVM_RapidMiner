# Non Linear Regression using Suport Vector Machine (SVM)

## Abstract
Regression analysis helps one understand how the typical value of the dependent variable (or 'criterion variable') changes when any one of the independent variables is varied, while the other independent variables are held fixed.  
The linear regression is performing the regression using only linear equation, but the non-linear regression can use polynomial equation.  
The used tool is RapidMiner.

## Import your Data
In this repository, I used "Read Excel" operator.  
If you want use the same operator, follow the steps:  
1- Open the xml file  
2- Go to line 16  
3- In "value" attribute of "parameter" tag, put the absolute path of your data excel file  

If you want use other operator to import data, import the process then change the operator.

## Import Process to RapidMiner
1- Clone  
2- (Optional) Import the excel data  
3- Change the extension of the xml file to rmp  
4- In the RapidMiner, import the rmp using "import process"  
5- Create your own data perprocessing and do something wonderful :)  

## Process
![alt text](https://github.com/MohammedElagha/Non-Linear-Regression-using-SVM/blob/master/nonlinear_regression_process.png)

## Methodology
The used tool in the non-linear regression is RapidMiner.  
The used algorithm in the non-linear regression is SVM. The SVM operator is set in the process, then another operator creates a model from SVM.  
Using Performance operator, the RapidMiner calculate the RMSE.  

## Parameters
The RapidMiner take some parameters related to SVM to be used in regression.  
1- SVM type is epsilon-SVR  
2- kernel type is polynomial  
3- degree of polynomial kernel function = 3 (you can change the degree).

## Result
The result of the process is the Root Mean Square Error (RMSE)
