# Week 1: Neural-Networks

<img width="585" alt="Screenshot 2024-03-25 at 2 22 52 PM" src="https://github.com/ColleenJung/Neural-Networks/assets/119357849/051d6319-5db0-4b76-ac16-a89f90e1a69c">

<img width="537" alt="Screenshot 2024-03-25 at 2 20 17 PM" src="https://github.com/ColleenJung/Neural-Networks/assets/119357849/1e582126-e2c3-471e-a3c2-21bec5c885ee">

# Perceptron
- Neutral networks functions in a way similar to biologocal neurons.
- Take in various **inputs** -> weight these inputs -> combine through a linear combi. ->if pass some threshold set by an *activation function* -> **output** sent out to other layers
- **activation function** is often non-linear as it is a linear combination.(predictor-target variables)
- Therefore useful for nonlinear functions
- It is of two types, Single-layer Perceptron does not contain *hidden layers.* Whereas, Multi-layer Perceptron contains one or more hidden layers.
- 
<img width="576" alt="Screenshot 2024-03-25 at 2 50 28 PM" src="https://github.com/ColleenJung/Neural-Networks/assets/119357849/181a9579-e6dc-4801-9018-1251ea07b412">

# Backpropagation
- learning process for Neutral networks
- Modifies the weights of the neural network iteratively, via calculating deltas between predicted and expe cted outputs
- After calculation, the wieghts are updated backward through erlier layers via stochastic gradient descent
- Continues untill the weights that minimizes the loss function are found

## Optimized loss function
- Regression: Mean Squared Error
- Classification: Cross-entropy

# Types of Neural Networks
1. Convolutional neural networks(CNNs)
- used in computer vision because they can capture the spatial dependencies of an image through a series of filters
2. Recurrent neural networks(RNNs)
- used in learning sequencial data such as audio or video and use their internal state(called memory)
3. Long Short-Term Memory(LSTMs)
- Fancier version of RNNs
