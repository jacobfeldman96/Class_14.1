# Class 14.1: Intro To Neural Networks

December 12, 2020

In the first hour of today's class we reviewed Amazon Lambda and Amazon Lex. Amazon Lex is the bot building platform in Amazon Web Services and Lambda is a serverless computing platform that enables users to run code on the backend of a GUI/CUI. We further reviewed the necessity to test edge cases on the Lambda code so that the bot can recognize when a certain necessary criteria is not met or distorted. 

## Artificial Neural Networks

Artificial Neural Networks (ANNs) were developed and modelled in the early 1940's. Mathematicians and Neurophysiologists believed that the human brain's processes could be mapped into mathematical sequences. The model itself was based on the neuron. Neurotransmitters and hormones, i.e. information, is received by a neuron's dendrites. That information is then carried to the cell's nucleus to be processed and the consequent message is passed down the axon to the axon terminal to signal to the next cell what to do and the process continues. So too in the mathematical, there is a perceptron (cell body) that receives information from its dendrites, input data signals. The information is processed in the hidden layer (nucleus) and classifies the result. Like our lack of fundemental explainability of the human brain, the process by which Neural Networks arrives at a given conclusion is impossible to explain.

Neural Networks are predominantely used for image recognition, security, and self driving cars. In business, ANNs can be applied to money laundering, risk management, foreign exchange and algorithmic trading. 

ANN's are used for classification problems and on their most basic level are effectively high powered linear regression models. However, through the activation functionality of an ANN, the nodes begin to extract non-linear data relationships which converts the output to a statistical range of options as opposed to a definite 0 or 1. 

The current issue with ANNs is their propsensity towards biased outputs. The bias is developed in the training data and evolves to various degrees as the data passes through the perceptrons. The lower the loss score, the higher the accuracy. 

Tensorflow is the library which we will be using for ANNs as it is wonderful for hypertuning parameters. Understanding the data and hypertuning its parameters is crucial for producing accurate ANN predicitions. 