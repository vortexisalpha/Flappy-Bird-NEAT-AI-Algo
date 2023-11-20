# Flappy-Bird-NEAT-AI-Algorithm


This is a flappy bird game coded in pygame with a NEAT
artificial intelligence algorithm to play the game.
NEAT stands for Neuro Evolution of Augmenting Topologies.
It is essentially an algorithm based on natural selection.

I plan on feeding 3 pieces of information
to an input layer in a neural network: The bird y position
the distance to the top pipe and the distance to the bottom pipe.
The output neuron will be a value of 1 or -1: 1 being jump and
 -1 being don't jump (hyperbolic tan activation function [tanh])

 Each generation will have 100 birds and the top x% of them will
 be mutated (make babies) for the next generation.

 The neural network will make itself more complex by adding 
 neurons, connections and layers by itsself to get the best 
 size for efficiency.
