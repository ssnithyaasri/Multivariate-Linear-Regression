# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
##Developed by:Nithyaa sri S S
##reference no:22008434
import pandas as pd
from sklearn import linear_model
df = pd.read_csv("cars.csv")
x = df[["Weight","Volume"]]
y = df["CO2"]
regr = linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2 = regr.predict([[3300,1300]])
print("Predicted CO2 for the correspondig weight and volume",predictedCO2)

```






```
## Output:


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
