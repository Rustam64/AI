# Predictive Maintenance for Conveyor Belts

## Overview
This project aims to implement predictive maintenance for conveyor belts using machine learning. The goal is to detect potential failures or anomalies in the system based on sensor data, specifically temperature, vibration, and belt speed.

## Data Generation
We generated synthetic sequential data for temperature, vibration, and belt speed. The data was created with and without failure scenarios to simulate real-world conditions. The failure probability was set to 10%.

<img width="443" alt="1" src="https://github.com/Rustam64/AI/assets/83468895/17741b26-e5a5-443e-a143-bd69d7ee60ad">

## Model Architecture
We used a Long Short-Term Memory (LSTM) neural network for predictive maintenance. The model architecture is as follows:
- LSTM layer with 32 units and ReLU activation function.
- A dense layer with 1 unit.

## Training Process
The data was preprocessed by standardizing the values. Then, it was split into training and testing sets. We used the mean squared error as the loss function and the Adam optimizer for training.

<img width="438" alt="2" src="https://github.com/Rustam64/AI/assets/83468895/581d943a-eec3-4019-b9b2-bd9b8797d15e">


### Training Parameters
- Number of epochs: 40
- Batch size: 32

The model was trained on the standardized temperature data. Training was repeated for a total of 10 iterations to ensure model stability and consistency.

## Results
The results of the predictive maintenance model are not included in this code but should be added to the report based on the actual project results.

## Conclusion
This README report provides an overview of the predictive maintenance project for conveyor belts. The model architecture and training process were outlined, and synthetic data was generated to simulate real-world conditions. The results of the model's predictive capabilities should be documented separately.

For more detailed information, please refer to the project's code and documentation.
