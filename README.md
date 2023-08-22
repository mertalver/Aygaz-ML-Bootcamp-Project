# Medical Cost Analysis

Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance <br>

In this project, you will be trying to develop an end-to-end data science application using the
dataset given above. The aim of the project is to estimate the approximate cost of a person's
health insurance based on the given variables. While creating the project, try to follow the
instructions below and make sure that the project is unique. <br>

## 1. Creating a Google Colaboratory File
● Make sure your project has .ipynb extension. <br>
● Make sure that there are comment lines explaining the details in your project <br>
● When submitting the project, submit the cells of this .ipynb file so that the cells are run and the results are visible.<br>

## 2. Importing Required Libraries
● Import the required libraries for the project to the Colab environment.<br>
● Import Pandas, NumPy, Seaborn, Matplotlib and Sklearn libraries for data analysis<br>

## 3. Perform An Exploratory Data Analysis
● Analyze the data and draw meaningful conclusions from the data. <br>
- Examine the distribution of Bmi (Body Mass Index) <br>
- Examine the relationship between “smoker” and “charges” <br>
- Examine the relationship between “smoker” and “region”. <br>
- Examine the relationship between “bmi” and “sex”. <br>
- Find the "region" with the most "children". <br>
- Examine the relationship between “age” and “bmi”. <br>
- Examine the relationship between “bmi” and “children”. <br>
- Is there an outlier in the "bmi" variable? Please review. <br>
- Examine the relationship between “bmi” and “charges”. <br>
- Examine the relationship between “region”, “smoker” and “bmi” using bar plot. <br>

● Try to use data visualization techniques as much as possible while examining the data. <br>
● Please add the meanings you deduced from the analyzes as a comment line. <br>

## 4. Data Preprocessing
● In this section, prepare the data you have, for training the model. <br>
● Use Label Encoding and One-Hot Encoding techniques to deal with categorical variables. <br>
● Split your dataset into X_train,X_test, y_train, y_test. <br>
● Scale the dataset by normalizing it(Min-Max Scaling or Standard Scaling). <br>

## 5. Model Selection
● Select several regression models and train them with the preprocessed data. <br>
● Examine the performances of the selected models using cross validation. <br>
● Choose the best performing model <br>

## 6. Hyper-parameter Optimization
● Optimize the hyper-parameters of the model selected in the previous step. <br>
● Optimize parameters with Grid Search. (Grid Search or Randomized Search) <br>

## 7. Model Evaluation
● Evaluate the optimized model using regression model evaluation metrics. (Ex. Mean Squared Error, Mean Absolute Error etc.) <br>
