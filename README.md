# Neural_Network_Charity_Analysis
## Analysis Overview
The goal of this project is to examine and categorize the success of charitable donations using deep-learning neural networks and the TensorFlow framework in Python.
For the analysis, we employ the following methods:
- Preprocessing the data for the neural network model,
- Compile, train and evaluate the model,
- Optimize the model
## Results
### Data Preprocessing
- The identity information columns `EIN` and `NAME` have been deleted from the input data.
The binary data in the `IS SUCCESSFUL` column indicates whether or not the charity donation was effective. The goal variable for our deep learning neural network is then this variable.
- The features for our model are the columns `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, `ASK_AMT`.
- The categorical variables were encoded, the training and testing datasets were split, and the features were standardized.
### Compiling, Training, and Evaluating the Model
- There are two hidden layers in this deep-learning neural network model, each comprising 80 and 30 neurons.\
There are 43 features and 25,724 samples in the input data.\
Because this is a binary classification, the output layer is made up of a single neuron.\
For the hidden layers, we use the activation function `ReLU` to speed up the training process. `Sigmoid` is employed on the output layer since our output is a binary categorization.\
The optimizer for this compilation is `adam`, and the loss function is `binary_crossentropy`.

## Summary

## Contact:
- Email : [neda.ahmadi.jesh@gmail.com](mailto:neda.ahmadi.jesh@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)
- Linkedin: www.linkedin.com/in/neda-ahmadi-j
