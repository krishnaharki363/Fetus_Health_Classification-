# Summary

## Fetal Health Classification App

This project is a **desktop-based Fetal Health Classification Application** developed using **Python Tkinter** for the graphical user interface and **Machine Learning** for prediction. The application is designed to classify fetal health status into three categories: **Normal, Suspect, and Pathological** based on **Cardiotocography (CTG) data**.

## Project Purpose

The main goal of this application is to help analyze fetal health readings using important CTG parameters and provide an easy-to-use interface for prediction, data exploration, and model evaluation. It demonstrates how statistical analysis, visualization, and machine learning can be combined into one interactive application.

## Main Features

- **Prediction System**  
  Users can input 21 CTG features through sliders and generate a fetal health prediction instantly.

- **Health Classes**
  - **Class 1 – Normal**
  - **Class 2 – Suspect**
  - **Class 3 – Pathological**

- **Probability Display**  
  The application shows prediction confidence and probability bars for all three classes.

- **Feature Importance**  
  For the Random Forest model, the app displays the most important features contributing to the prediction.

- **Exploratory Data Analysis (EDA)**  
  The app includes multiple visualization options:
  - Class distribution
  - Feature histograms
  - Correlation heatmap
  - Boxplots by class
  - PCA scatter plot

- **Model Performance Evaluation**  
  Users can train and compare:
  - **Random Forest Classifier**
  - **Logistic Regression**

  The app also displays:
  - Accuracy
  - Confusion matrix
  - Precision, Recall, and F1-score charts

## Technical Overview

The application uses:
- **Tkinter** for GUI development
- **Pandas** and **NumPy** for data handling
- **Matplotlib** and **Seaborn** for visualization
- **Scikit-learn** for machine learning and preprocessing

A synthetic dataset is generated within the code to mimic real CTG data distribution. The dataset contains **2,126 samples**, **21 features**, and **3 fetal health classes**.

## Conclusion

This application is a complete machine learning-based healthcare analysis tool that combines prediction, visualization, and evaluation in one modern interface. It is useful for academic learning, demonstration of applied statistical analysis, and understanding how fetal health classification works using CTG data.