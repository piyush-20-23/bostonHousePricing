# Boston House Price Prediction – End-to-End Machine Learning Project

## 📌 Project Overview
This was a learning project for my understand of how to develop and deploy a ML model which can be accessed by internet.
The ML model for this project was very simple as i was in the process of learning how to deploy the ipynb file instead of to build a useful model.

Project specification are - <br>
This project implements an **end-to-end Machine Learning pipeline** to predict **median house prices in Boston suburbs** using the **Boston Housing Dataset**.  
The project covers the complete lifecycle of an ML system — from **dataset understanding and exploratory data analysis (EDA)** to **model training, evaluation, deployment, and web-based prediction**.

The goal is to demonstrate how a regression-based ML model can be developed, analyzed, and deployed as a **production-ready web service**.

---

##  Dataset Description

The **Boston Housing Dataset** is available in `sklearn.datasets` and contains information collected by the U.S. Census Service.

- **Number of instances:** 506  
- **Number of features:** 13  
- **Target variable:** Median value of owner-occupied homes (in thousands of dollars)


## Data Analysis 

- Converted dataset to Pandas DataFrame

- Added feature names and target column (price)

- Checked data types, statistics, and missing values

- Performed correlation analysis and visualizations

## Key insights: 

- RM has a strong positive correlation with price

- LSTAT has a strong negative correlation with price

## Model Training 

- Algorithm: Linear Regression

- Train-test split: 70% / 30%

- Feature scaling using StandardScaler

- Trained on scaled data

## Prediction 

- Predictions generated on test data

- Model performance evaluated using visual comparison

- Trained model saved using pickle (regmodel.pkl)

## Web Application 

- Built using Flask

- Accepts user input through a web form

- Displays predicted house price

## Deployment

- Version control using GitHub

- Deployed as a web service (Heroku / Docker / Render)

## Tools Used

- Python

- Pandas, NumPy

- Scikit-learn

- Matplotlib, Seaborn

- Flask

- Git & GitHub

## Outcome

A working machine learning web application that predicts house prices based on user input.
