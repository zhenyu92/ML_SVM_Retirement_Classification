# A study on Customer Retirement Classification using Support Vector Machine (SVM).
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
You work as a data scientist at a major bank in NYC.
You have been tasked to develop a model, that can predict whether a customer is able to retire or not based on his/her features. 
Features are his/her age and net 401K savings (retirement savings in the U.S.). 

`Predictors:`
```
Customer ID
Age
401K Savings
```

`Target:`
```
Retire (1: Able, 0: Not Able)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_SVM_Retirement_Classification/blob/master/Bank_Customer_retirement.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_SVM_Retirement_Classification/blob/master/SVM%20-%20Bank%20Customer%20Retirement%20Predictions.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Visualizing the Variables
    4 Train Test Split
    5 Select and Train a Model
      5.1 Support Vector Machine Model
    6 Apply Model on Test Set
      6.1: Improving the Model
      6.2 Applying GridSearch
    ```
    
### Model Performance
The model has an average `Precision` & `Recall` of 94%.
![alt text](https://github.com/zhenyu92/ML_SVM_Retirement_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
