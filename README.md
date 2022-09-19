# Dog-Breed
For us, humans, it is pretty easy to tell one dog breed from another. That is if you are talking about 10–20 popular dog breeds. When we are talking about more than 100 kinds of dogs, it is an entirely different story. For a human to correctly and consistently classify a large number of breeds, we need a different approach than just pure memorization. We need to start extracting “features” that correspond to different breeds such as fur color, ear shape, facial shape, tail length, etc. Even then, we need to memorize what breed has what features, and it’s not an easy or fun task.
Humans having difficulties identifying a large number of species is a perfect example of situations where computers are better than us. This is not to say that Skynet is coming to kill us all; I believe that we should not worry about that just yet. Instead of machines replacing humans in the workforce, many believe that a hybrid approach of the two races working together can outperform any single race working alone. You can read more about the topic in the book titled Machine, Platform, Crowd by Andrew McAfee.

In this project, I will walk you through the steps to build and train a convolutional neural network (CNN) that will classify 133 different dog breeds. This project is part of my Data scientist Nanodegree, and you can find out more about it here. The code for this project is available on my GitHub repo, make sure that you install the required packages if you want to follow along.
We are very good at recognizing things thanks to millions of years of evolution that went into perfecting our eyes and brains for vision capability. A computer “sees” an image as a series of numbers. A pixel on your screen is represented as three numbers from 0 to 255. Each number is represented as the intensity of red, green, and blue. 
Traditionally, it’s tough for a computer to recognize or classify an object in an image. With the recent advancements in computing power and neural network research, computers can now have human-level vision capability on many specific tasks.

What is a neural network
There are many great resources out there explaining what a neural network is. Here’s my favorite explanation borrow from this post:

Neural Networks consist of the following components

An input layer, x
An arbitrary amount of hidden layers
An output layer, ŷ
A set of weights and biases between each layer, W and b
A choice of activation function for each hidden layer, σ. In this tutorial, we’ll use a Sigmoid activation function.


