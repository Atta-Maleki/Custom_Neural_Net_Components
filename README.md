# Custom_Neural_Net_Components
How can we customize the components of a Neural Network? We can replace any component of the NN with a personalized or modified version. This repository contains useful codes for people interested in building a Neural Network from scratch. You will even learn how Gradient Descent works and be able to write your own Gradient Descent function. If you’re wondering why it’s important to customize each component, the answer is that it’s not that important if you’re just using the application of NN for your projects and it’s not your field. However, if you want to know how it works and what happens in deeper parts of the back-stage, have a look at the codes inside the repository.
Content List
---

- **AdamOptimizerGradients.ipynb**: This file contains a callable and runnable class for the Adam optimizer, which is a popular optimization algorithm used in neural networks.

- **Custom_Activation_Function.ipynb**: The main point of this code is to show how a node inside a classic neural network calculates the output. We replace our activation function called `myLayerClass` with `Dense`, and it works well.

- **Custom_Layer.ipynb**: The "Hello World" of neural networks should work well with the node we defined in the previous code. So we can train a neural network with a layer containing only one node, one input, and one output.

- **Custom_Weights.ipynb**: Everything is normal in this file. There is only one line of code showing that we can access a weight matrix inside a neural network after compiling it. We can assign new values or use them after fitting them to any dataset.

- **Linear_Regression_Gradients.ipynb**: We always fit the model on a dataset and see that epochs rise and gradient descent applies to the model. Outputs get closer and closer to the ground truth, so we use a custom database on a custom formula and then we use nested gradients. Without using the `model.fit` function, we train a model.

- **Manual_HelloWorldOfNN.ipynb**: After knowing how to implement any important part of a neural network, we can implement a neural network for the "Hello World" of neural networks. I chose a simple problem to make it easy to understand what is going on.

- **Manual_Huber_Loss.ipynb**: We all used Huber Loss before and know the formula. So we can implement it manually. The file contains a manual Huber Loss function, and we call our manually implemented Huber Loss function while we compile the model.

Source: Conversation with Bing, 12/20/2023
(1) How do you create a custom activation function with Keras?. https://stackoverflow.com/questions/43915482/how-do-you-create-a-custom-activation-function-with-keras.
(2) 02-activation-functions.ipynb - Colaboratory - Google Colab. https://colab.research.google.com/github/PytorchLightning/lightning-tutorials/blob/publication/.notebooks/course_UvA-DL/02-activation-functions.ipynb.
(3) C1_W3_Lab_3_custom-layer-activation - GitHub. https://github.com/BenjiKCF/Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/blob/main/C1_W3_Lab_3_custom-layer-activation.ipynb.html.
(4) Custom activation functions with trainable parameters. https://discuss.pytorch.org/t/custom-activation-functions-with-trainable-parameters/52186.
