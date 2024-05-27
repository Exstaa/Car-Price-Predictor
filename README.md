# Car Price Predictor
This project is a Car Price Predictor application built with Python and Streamlit. It allows users to predict the selling price of a car based on various features using a machine learning model.

## Overview
The Car Price Predictor application takes input features such as car make, model, year, mileage, and other relevant attributes to predict the selling price of a car. The prediction is made using a machine learning model trained on historical car price data.

## Features

- User-friendly interface built with Streamlit
- Input fields for various car features
- Predicts car prices based on input features
- Displays the predicted price and relevant statistics
- Data visualization for better insights

## Installation

To run the Car Price Predictor application locally, follow these steps:

1. Clone the repository:

    ```sh
    git clone https://github.com/Exstaa/Car-Price-Predictor.git
    ```

2. Navigate to the project directory:

    ```sh
    cd car-price-predictor
    ```

3. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the dataset file in the project directory.
2. Run the Streamlit application:

    ```sh
    streamlit run app.py
    ```

3. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).

4. Enter the car features into the input fields and click the "Predict" button to see the predicted price.

## Dataset

The dataset used for training the machine learning model should contain relevant features such as:

- Make
- Model
- Year
- Mileage
- Fuel type
- Transmission
- Owners
- Selling price (target variable)

Ensure your dataset is clean and preprocessed for optimal performance.

## Model

The machine learning model used for prediction is trained using the following steps:

1. Data cleaning and preprocessing
2. Feature selection and engineering
3. Model training using algorithms such as Linear Regression, Random Forest, or Gradient Boosting
4. Model evaluation and tuning for better accuracy
