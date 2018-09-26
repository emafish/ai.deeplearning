# ai.deeplearning (week4_1)

def initialize_parameters(n_x, n_h, n_y):
    return parameters  
    
def initialize_parameters_deep(layer_dims):
    return parameters
    
def linear_forward(A, W, b):
    return Z, cache
    
def linear_activation_forward(A_prev, W, b, activation):
    return A, cache
    
def L_model_forward(X, parameters):
    return AL, caches
    
def compute_cost(AL, Y):
    return cost
    
def linear_backward(dZ, cache):
    return dA_prev, dW, db
    
def linear_activation_backward(dA, cache, activation):
    return dA_prev, dW, db
    
def L_model_backward(AL, Y, caches):
    return grads
    
def update_parameters(parameters, grads, learning_rate):
    return parameters
    
# ai.deeplearning (week4_2)
# Question: Use the helper functions you have implemented in the previous assignment to build a 2-layer neural network with the following structure: LINEAR -> RELU -> LINEAR -> SIGMOID. The functions you may need and their inputs are:
def initialize_parameters(n_x, n_h, n_y):
    ...
    return parameters 
def linear_activation_forward(A_prev, W, b, activation):
    ...
    return A, cache
def compute_cost(AL, Y):
    ...
    return cost
def linear_activation_backward(dA, cache, activation):
    ...
    return dA_prev, dW, db
def update_parameters(parameters, grads, learning_rate):
    ...
    return parameters
    
# 5 - L-layer Neural Network
# Question: Use the helper functions you have implemented previously to build an  L
#  -layer neural network with the following structure: [LINEAR -> RELU] ×
# (L-1) -> LINEAR -> SIGMOID. The functions you may need and their inputs are:
def initialize_parameters_deep(layers_dims):
    ...
    return parameters 
def L_model_forward(X, parameters):
    ...
    return AL, caches
def compute_cost(AL, Y):
    ...
    return cost
def L_model_backward(AL, Y, caches):
    ...
    return grads
def update_parameters(parameters, grads, learning_rate):
    ...
    return parameters
