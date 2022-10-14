# Neural_Network_Charity_Analysis

## Results
For this analysis and model, the target is held in IS_SUCCESSFUL field.

The following variabls should be considered on features model
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE

The following variables) should be removed from input and data.
NAME
EIN
Compiling, Training, and Evaluating the Model
Model Configuration:

hidden_nodes_layer1 = 80
hidden_nodes_layer2 = 30
number_input_features = 43
This model acheived 63.8% accuracy with several attempts to incraese the accuracy including:
Increasing the number of hidden nodes in layer 1 (3 X number of input features)
Increasing the number of hidden layers to include a 3rd
Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer


## SUMMARY
Our Analysis and Deep Learning Model Results include a recommendation for how a different model could solve this classification and results.
