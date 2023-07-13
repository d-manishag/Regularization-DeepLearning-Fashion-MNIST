# Regularization-DeepLearning-Fashion-MNIST
An Experimental Study of  What Makes Deep Neural Networks Generalize Well  - The Role of Regularization using Fashion MNIST

The regularization effect is studied by experimenting and bhulding Deep learning models to classify the Fashion MNIST dataset. The following are the different DL models used in our study.
- Convolutional Neural Network (CNN)
- Multi-Level Perceptron (MLP)
- Visual Geometry Group 16 (VGG16)
The above models are built with and without Regularization to see how much effect Regularization has in the case of accurate classifying and improving accuracy.

## Regularization Techniques
Regularization refers to a set of different techniques that lower the complexity of a neural network in order to prevent overfitting
Neural networks easily fit most of the data given to them 
Most common explicit regularization techniques are dropout and weight decay.
Reduce the effective capacity of the model and typically require the use of deeper and wider architectures to compensate for the reduced capacity

### Explicit Reggularization
- L2 Regularization (Weight Decay) - Works in reducing overfitting by forcing the weights to decay
- Dropout - Works removing reliance on individual neuron
  

## Conclusion
Neural networks have effective capacity and are large enough to shatter training data.
Traditional measures of model complexity struggle to explain the generalization of large neural network.
Optimization continues to be easy even when generalization is poor.
Both explicit and implicit regularizers could help to improve the generalization performance.
However, it is unlikely that the regularizers are the fundamental reason for generalization.


Reference - https://dl.acm.org/doi/pdf/10.1145/3446776


