🌞 Predicting Solar Panel Energy Output Using Multiple Linear Regression
📌 Project Overview

This project builds a Multiple Linear Regression model to predict solar panel energy output based on:

    Temperature
    Solar Irradiance
    Wind Speed
    Humidity

The dataset is synthetically generated using a predefined linear relationship with added noise. The model is implemented using scikit-learn.
📊 Dataset Description

The dataset contains 1000 samples, where:

    Temperature (°C): Randomly generated between 10 to 40°C.
    Solar Irradiance (W/m²): Randomly generated between 300 to 1000 W/m².
    Wind Speed (m/s): Randomly generated between 0 to 10 m/s.
    Humidity (%): Randomly generated between 10 to 90%.
    Energy Output (W): Calculated using a linear function with noise.

📈 Model Evaluation

The model's performance is assessed using:
✅ Mean Squared Error (MSE)
✅ R² Score
✅ Visualization of predictions vs actual values
