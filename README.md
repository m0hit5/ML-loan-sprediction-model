
# ML Loan Prediction App

This repository contains the code for a Loan Prediction App built using Flask and a machine learning model stored as a Pickle file. The app predicts the likelihood of loan approval based on various input features.

## Table of Contents
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Pickle File](#pickle-file)
- [Web Application](#web-application)
- [Deployment](#deployment)
- [Tech Stack](#tech-stack)
- [Usage](#usage)

## Dataset

The dataset used for this project is available on Kaggle: [Loan Data Set](https://www.kaggle.com/datasets/burak3ergun/loan-data-set).

## Preprocessing

- Filled missing values in the dataset.
- One-Hot Encoded the categorical data to convert it into a format suitable for machine learning models.

## Model Training

- Trained and tested the model using both regression and classification algorithms.
- Achieved 91% accuracy using the RandomForest classification algorithm.

## Pickle File

- Created a Pickle file of the trained model to save the model for later use without retraining.

## Web Application

- Used the Flask microframework to build a web application.
- Implemented RestAPI for handling HTTP requests and responses.

## Deployment

- Deployed the model on [PythonAnywhere.com](https://www.pythonanywhere.com).

## Tech Stack

**Client:** HTML, CSS

**Server:** Python, Flask, RestAPI

**Other:** Pickle file, Scikit-Learn

**Deployment Service:** PythonAnywhere.com

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ml-loan-prediction-app.git
    cd ml-loan-prediction-app
    ```

2. Install the required packages:
    ```bash
    pip install Flask
    pip install scikit-learn
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```
