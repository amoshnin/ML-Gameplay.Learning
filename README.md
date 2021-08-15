# Flappy Bird

Artificial intelligence lerns how to play Flappy Bird by utilizing Neural Networks (Tensorflow) with Genetic Algorithm (NEAT)
![Flappy Bird Game Preview](./docs/game_preview.png)

## Requirements

Python 3.6 or below
numpy
pygame
neat-python
graphviz
matplotlib

## Explanation of the Neural Network and Genetic Algorithm

In this project the AI teaches itself how to play Flappy Bird.
The way this works is that it starts completely random, having no idea what to do and how the game even operates.
Only after many generations of slowly learning and getting better, it finally picks up on patterns on what it can do to progress further in the level.

To achieve this, Genetic Algorithms and Neural Networks are being used together.
[Genetic Algorithm is a part of Evolutionary Algorithms](https://www.mygreatlearning.com/blog/introduction-to-genetic-algorithm/), specifically to generate high-quality solutions to optimization and search problems by relying on biologically inspired operators such as mutation, crossover, and selection. In this [article](https://towardsdatascience.com/gas-and-nns-6a41f1e8146d) you can read a great evaluation on using Neural Networks (NNs) with Genetic Algorithms (GAs) to accelerate the learning process.

The actual algorithm used is called NEAT = NeuroEvolution of Augmenting Topologies
After a few generations, the AI starts to get exponentially better. Until eventually it reaches the point where it cannot be beaten. It can beat the level infinetely and keep going without ever hitting a pipe. To me, this is increadibly fascinating!

To understand the full picture, let's firstly understand how Neural Networks work in this scenario.

## Source of inspiration

Inspiration for this project was taken from CodeBullet.
