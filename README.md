# Predict Crop Yield Flutter APP

This Flutter app, integrated with a Flask backend, predicts agriculture yield based on input parameters such as area, item, year, average rainfall, pesticides usage, and average temperature. The machine learning model, implemented using a Random Forest algorithm, is trained on historical agriculture data.

## Features

- **Frontend in Flutter**: User-friendly interface to input agricultural parameters and receive yield predictions.
- **Backend in Flask**: API to handle incoming requests, process data, and return predictions.
- **Machine Learning Model**: Utilizes a Random Forest model trained on historical agriculture datasets to make yield predictions.
- **Modular Code Structure**: Separation of frontend and backend logic for better organization and maintainability.
- **HTTP Requests with `http` Package**: Communication between Flutter app and Flask backend through HTTP POST requests.
- **Example Usage**: A basic example demonstrating how to use the Flutter app to interact with the Flask API.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/hasibullah1811/predict-crop-yield-flutter-app
   cd agriculture_yield_prediction
   ```
