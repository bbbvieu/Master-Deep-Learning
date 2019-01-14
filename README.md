# Master-Deep-Learning

As part of the machine learning teaching unit at ENSEEIHT in the computer science and applied mathematics department, 
this repository contains the sources of our Master 2 project, each one dealing with a concept from neural network theory.
This project was made with pytorch in a jupyter-notebook environment.

## Rock Paper Scissors

The first exercise is based on the "rock/paper/scissors" game and propose a solution to detect in which configuration a hand is.
Naturally, we worked on little size image (32x32) to propose a classification in 3 possible states (rock, paper, or scissors). We built a little dataset (about 200 labelled images) to train a linear network composed of 3 layers. Unfortunately, the result obtained was not satisfactory, indeed we reach a 55% accuracy which is not really good for a problem as simple as this. But it can be explained with a bad dataset and the fact that a linear neural network model is maybe not adapted to get performance on image recognition.

Source: rock_paper_scissors.ipynb

## Autoencoder

The second exercise was to setup a variational autoencoder to reconstruct a set of number (32x32 images). An autoencoder is not so different of a multilayer perceptron, the point is the output data has the same type of the input one. Actually there is 2 steps in an autoencoder, the encode part (2 linear layers in our case) which compresses the data into what it thinks is the most useful information and the decode part (2 linear layers also) which takes this compressed information to recreate the data. In this TP we successfully remove the noises of number images to reconstruct clear and readable ones.

Source: autoencoder.ipynb / VAE.ipynb

## Adverserial Network

Source: adverserial_images.ipynb

## Recursive Neural Network

The last exercise consisted in applying a recursive neural network to predict future values of a time sequence. RNN are particulary adapted for that kind of issues, indeed it retains past information and allows us to create a kind of consistency between what we predict and what happened or what we predicted before. We used two kinds of network, a simple RNN and the LSTM variant.

Source: RNN.ipynb


This project was carried by Oumaima Sohab and Bastien Vieublé

N7: http://www.enseeiht.fr
