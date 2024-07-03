# deep-learning-challengeOk
Report on the Neural Network Model for Alphabet Soup

Overview of the Analysis
The purpose of this analysis is to create a binary classifier using a deep learning neural network to predict whether applicants for funding from Alphabet Soup will be successful. By analyzing historical data on previous applicants, the model aims to help the organization identify the most promising candidates for future funding.

Data Preprocessing

• Target Variable(s):
IS_SUCCESSFUL: This variable indicates whether the funding was used effectively (1 for successful, 0 for not successful).

• Feature Variable(s):
All columns except EIN, NAME, and IS_SUCCESSFUL.

• Variables Removed:
* EIN: Employer Identification Number, a unique identifier for organizations.
* NAME: The name of the organization.

Compiling, Training, and Evaluating the Model

•	Neurons, Layers, and Activation Functions:
* First hidden layer: 80 neurons, ReLU activation function.
* Second hidden layer: 30 neurons, ReLU activation function.
* Output layer: 1 neuron, Sigmoid activation function.

The model was chosen based on a balance between complexity and performance. ReLU activation functions were used for hidden layers due to their effectiveness in deep learning models, while the sigmoid function was used in the output layer for binary classification.

• Target Model Performance:
•	The model's performance was evaluated using accuracy and loss metrics.

• Optimization Attempts:
* Adjusting the number of neurons and layers.
* Using different activation functions.
* Tuning the number of epochs

Summary
The deep learning model was successfully trained to predict the success of applicants for funding from Alphabet Soup. The model's architecture included two hidden layers with ReLU activation functions and an output layer with a sigmoid activation function. Despite various optimization attempts, achieving a target accuracy above 75% may require further adjustments, such as additional hidden layers, different activation functions, or more epochs.
