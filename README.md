![](BHP_website.PNG)

This data science project series walks through step by step process of how to build a real estate price prediction website. We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. Second step would be to write a python flask server that uses the saved model to serve http requests. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedroom etc and it will call python flask server to retrieve the predicted price. During model building we will cover almost all data science concepts such as data load and cleaning , outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc. Technology and tools wise this project covers,

1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI

# 🏠 Real Estate Price Prediction

A machine learning-powered web application that predicts **real estate property prices** based on features like area, location, number of rooms, and amenities.  
This project demonstrates an end-to-end ML workflow — from data preprocessing and feature engineering to model training and **Flask web deployment**.

---

## 🚀 Overview

The application enables users to input property details through an intuitive **web interface**, then returns an estimated price instantly.  
It integrates a trained regression model built with Scikit-learn and uses Flask for backend deployment.

---

## 🧠 Key Features

- 🧹 **Data preprocessing:** Handling missing values, outlier removal, and feature encoding  
- 📈 **Regression modeling:** Linear Regression / Random Forest for price prediction  
- 💾 **Model persistence:** Uses `pickle` to save and load trained models  
- 🌐 **Interactive Flask web app** for real-time predictions  
- 📊 **Visualization support** for EDA and feature insights  

---



