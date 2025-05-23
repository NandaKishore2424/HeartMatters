# Heartmatters (Cardio-Monitor) Project Analysis

## Project Overview

This project is a heart disease prediction web application called "Cardio-Monitor" that helps users determine if they're at risk of developing heart disease. According to the README, the prediction model achieves 92% accuracy.

## File Structure and Purpose

### Backend Files

app.py: Flask application that serves as the main entry point, handling routes and web requests
modelbuild.py: Contains functions for building and training the machine learning model, importing data, and connecting to MongoDB
prediction.py: Handles the prediction logic when users submit their health parameters
database.py: Manages database operations and storage of prediction results
visualization.py: Creates data visualizations for the web interface

### Frontend Files

home.html: Main page with a form where users enter their health information
result.html: Page that displays prediction results after form submission
templates/about.html: Information page about heart disease (referenced but not fully shown)
static/: Contains assets like images (includes heartlogo.png)

### Jupyter Notebooks

heart disease prediction/Notebooks/Early Detection of Heart Disease Using Big Data Approach.ipynb: Contains data analysis, feature engineering, and model training
heart disease prediction/Notebooks/Heart Disease Detetction Using Big Data Approach-best accuracy-git.ipynb: Similar notebook with optimized model for higher accuracy
heart disease Heart_Disease_Prediction.ipynb: Another variation of the analysis and modeling

### Documentation

README.md: Project overview and description
heart disease README.md: Information about the heart disease prediction component

## Technology Stack

Frontend
HTML/CSS
Bootstrap for responsive design
JavaScript (implied for interactivity)
Backend
Python 3
Flask web framework
Matplotlib for generating visualization images
Data Science & ML
Pandas for data manipulation
NumPy for numerical operations
Scikit-learn for ML algorithms
XGBoost for gradient boosting models
Pandas-profiling for automated EDA (Exploratory Data Analysis)
Matplotlib/Seaborn for data visualization
Database
MongoDB (with hints of MongoDB Atlas for cloud hosting)

## Project Output

The application:

Takes user input on health parameters through a web form
Processes this data through the trained prediction model
Returns a result indicating whether the user is at risk of heart disease
Stores the prediction data in MongoDB
Provides visualizations to help understand the results
