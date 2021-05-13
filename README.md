# BostonhousePrice-DecisionTreeRegression
```
-   CRIM : Per Capita crime rate by town
-   ZN : Proportion of residential land zoned for lots over 25,000 sq.ft.
-   INDUS : Proportion of non-retail business acres per town
-   CHAS : Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
-   NOX : Nitric oxides concentration (parts per 10 million)
-   RM : Average number of rooms per dwelling
-   AGE : Proportion of owner-occupied units built prior to 1940
-   DIS : Weighted distances to five Boston employment centres
-   RAD : Index of accessibility to radial highways
-   TAX : Full-value property-tax rate per $10,000
-   PTRATIO : Pupil-teacher ratio by town
-   B : 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
-   LSTAT : % Lower status of the population
```

## Load and Check all the data's correlation
As we can see the table and Heatmap below.

We can use this heatmap to find witch variables are the Positive correlation in Boston house price.

![alt text](https://raw.githubusercontent.com/ahoucbvtw/BostonhousePrice-DecisionTreeRegression/main/Picture/HeatmapTable.jpg "HeatmapTable")

![alt text](https://raw.githubusercontent.com/ahoucbvtw/BostonhousePrice-DecisionTreeRegression/main/Picture/Heatmap.png "Heatmap")


## Train
First, use sklearn's function **train_test_split** to split train and test data.

Then use DecisionTree to train, to do regression analysis for the house price.

![alt text](https://raw.githubusercontent.com/ahoucbvtw/BostonhousePrice-DecisionTreeRegression/main/Picture/DecisionTree.jpg "DecisionTree")


## Verification & Result
In test data, we used r² points to represent our regression model was the OK model.

```
r² points =  0.8096585156043419 
```
