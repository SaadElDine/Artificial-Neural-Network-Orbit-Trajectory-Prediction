# Meteor Trajectory Prediction
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/8158c834-c7cd-4d59-8c0d-f9656a13deff)

## Problem Statement
The goal is to predict the trajectory of a meteor based on given data.

## Data Preparation
Data consists of time steps and corresponding y positions.

## Model Development
- **Basic Model**: A basic neural network model with several dense layers.
- **Ensemble Model**: An ensemble of 400 neural network models, each with a similar architecture but trained independently.
  ### Orbits of 400 Models:
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/2aa85669-0c53-42da-8ebb-3ee1c0683575)

  ### Taking Avgerage Of all Models:
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/57c0ffc2-bad5-4bb6-aeb1-6615b82fdd76)

  ## Choosing the best Model:
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/77d0f07a-8add-48df-b661-e04cd3118bb6)

## Training
- **Model Training**: Both the basic and ensemble models were trained using the Adam optimizer and mean squared error loss.
- **Early Stopping**: Implemented early stopping based on validation loss to prevent overfitting.

## Model Evaluation
- **Validation Loss**: Used to determine the best model in the ensemble.
- **Custom Loss Function**: Developed a custom loss function combining mean squared error and mean absolute error.
- **Custom Metric**: Developed a custom metric based on mean absolute error.

## Model Visualization
- **Plotting Orbits**: Created functions to plot the predicted orbits of the models against the scientist's orbit.

## Future Improvements
- Further optimization of network architecture, hyperparameters, and training methodologies.
- Exploration of more advanced regularization techniques and ensemble methods.
- Development of custom loss functions and metrics tailored to the specific requirements of the problem.

## Final Orbits Comparasion 
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/6426f5aa-facc-484f-9213-50562c58ae84)


