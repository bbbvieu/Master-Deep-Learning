# Master-Deep-Learning

As part of the machine learning teaching unit at ENSEEIHT in the computer science and applied mathematics department, 
this repository contains few TP, each one dealing with a concept from neural network.
This project was made with pytorch in a jupyter-notebook environment.

## Rock Paper Scissors

The first exercise is based on the "rock/paper/scissors" game. The final goal is to detect in which configuration a hand is.
Naturally, we worked on little size image (32x32) to propose a classification. We built a little dataset (about 200 labelled images) to train a linear network composed of 3 layers. The result obtained was not satisfactory, indeed we reach a 55% accuracy which is not really good for a problem as simple as this. But it can be explained with a bad dataset and the fact that a linear neural network model is maybe not adapted to get performance on image recognition.

