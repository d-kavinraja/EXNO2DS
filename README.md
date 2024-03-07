## Ex No: 02
# Aim:
   To perform Exploratory Data Analysis on the given data set.
      
# Explanation:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# Algorithm:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## Coding and Output
```py
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
df=pd.read_csv("titanic_dataset.csv")
df
```
![1](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/5b7ee799-5b7a-4977-a592-29c35e4edc64)
![2](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/46bf2696-ab0e-45e3-8641-6d13a8683577)
![3](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/0c3dea80-6903-4c1a-98c7-6a45e3b22a9b)
![4](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/a4c8288c-75cc-4cf6-af5e-b1235bd7967e)
![5](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/3b07cd6a-9a36-465c-98aa-70fb8393f08a)
![6](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/99fc9b46-ff1f-41a8-b9f8-8c9e5e2d364d)
![7](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/daa76e0e-d84d-4356-9343-b9ae4a985756)
![8](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/88b202e3-9258-4eb1-9078-67fa5866c634)
![9](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/72037cca-d444-496c-a4bb-0abf09357e7c)
![10](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/181a6c12-35d8-4603-b8ba-c2ed32ccf3f3)
![11](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/aeb7f0a6-e23d-458a-aea5-4c32f07474e4)
![12](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/e630f061-1ed8-454c-a2b2-5741ed5d1cea)
![13](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/6d891b3d-e0bd-48c5-a2ff-152cec9759b8)
![14](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/265a5f63-e8a9-478d-8665-7188417b70f2)
![15](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/c3640710-8361-4a96-ab27-08902a164aac)
![16](https://github.com/abdulwasih2003/EXNO2DS/assets/91781810/7acf4aa5-772d-4437-a7fe-4fe6646ea783)
# Result:
Thus the Exploratory Data Analysis process is performed successfully on the given data using python code.
