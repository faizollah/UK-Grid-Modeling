# Carbon Intensity Prediction using Neural Networks
This project aims to predict the actual carbon intensity of the UK National Grid using forecasted values. The dataset used is sourced from the National Grid's Carbon Intensity API. The prediction model is built using a neural network implemented in Keras.

## Project Overview
The primary goal of this project is to understand the discrepancies between forecasted and actual carbon intensity values. By predicting actual values based on forecasted ones, we can gain insights into the factors affecting these discrepancies and potentially improve forecasting methods in the future.

## Data Preprocessing
- Data sourced from the National Grid's Carbon Intensity API.
- Features engineered include:
  - Difference between forecasted and actual intensity.
  - Rolling averages over certain intervals.
  - Time-based features like hour of the day and day of the week.
- One-hot encoding applied to categorical features.

## Model Architecture
- Neural network built using Keras.
- Input layer with 64 neurons.
- Hidden layer with 32 neurons.
- Output layer for regression prediction.
- ReLU activation function used in input and hidden layers.
- Linear activation function used in the output layer.

## Results
The model was trained and validated on a subset of the data. The mean squared error was used as the performance metric. Further details and results can be found in the Jupyter notebook included in the repository.

## Future Work
- Experiment with different neural network architectures.
- Incorporate additional data sources to improve predictions.
- Explore other machine learning algorithms for comparison.

## Acknowledgements
Thanks to the National Grid for providing the Carbon Intensity API.
