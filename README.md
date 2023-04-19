# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)

This dataset is used for images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. A total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains. It is a multi-variate classification Dataset.

Number of Instances: 13611

Number of Attributes: 17

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.77 | linear | 1.38 | 4.10 |
| 2 | 0.44 | linear | 1.24 | 5.82 |
| 3 | 0.48 | poly | 0.77 | 2.16 |
| 4 | 0.56 | linear | 1.27 | 1.27 |
| 5 | 0.38 | linear | 4.91 | 6.73 |
| 6 | 0.64 | poly | 1.05 | 6.93 |
| 7 | 0.40 | poly | 9.70 | 1.55 |
| 8 | 0.65 | linear | 6.10 | 4.47 |
| 9 | 0.37 | poly | 9.59 | 3.83 |
| 10 | 0.48 | poly | 2.02 | 4.64 |


## Convergence Graph
![graph](https://github.com/Jiteshgarg/Parameter-Optimization-SVM/blob/main/graph.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 1 has the best accuracy of 0.77 having kernel = linear, Nu = 1.38 and Epsilon = 4.10.

## Written By
Name : Jitesh Garg
  
Roll No. : 102017180

Sub-Group: 3CS8
