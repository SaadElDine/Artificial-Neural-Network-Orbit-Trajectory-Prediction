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
  ![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/38c1cc6e-ab2d-4242-b1c3-453533281a52)

  ### Taking Avgerage Of all Models:
  ![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/a4f758c2-19e2-494a-83e2-dc44d567afd3)

  ## Choosing the best Model:
  ![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/968955ff-fdac-464e-a023-10207475b179)

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
![image](https://github.com/SaadElDine/Artificial-Neural-Network-Orbit-Trajectory-Prediction/assets/113860522/6b0b206a-02a3-41e2-90a1-57da08bc675b)


