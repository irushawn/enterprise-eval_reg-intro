# Tuning Neural Networks with Normalization, Evaluation, and Regularization - Introduction

## Introduction


Now that you have a general sense of the architecture of neural networks and some of their underlying concepts, its time to further investigate how to properly tune a model for optimal performance.

Before we do that, we'll consider what is meant by *deep learning*, which are neural networks with multiple layers. In other words, these neural networks have a lot of depth; hence, *deep learning*.

## Evaluation

We're familiar with evaluation methods such as looking at metrics and using K-Folds. While we have naturally already used metrics with neural networks, we'll now see how to use validation methods like K-Folds. Additionally, we'll be introduced to `TensorBoard`, which is essentially a dashboard for `TensorFlow`. It will help us evaluate our model.

## Normalization

Another modeling problem occurs when one gets trapped into a local minimum when searching for an optimal solution using an iterative approach such as gradient descent. One technique for counteracting this scenario is normalizing features. Normalization in deep learning models can drastically decrease computation time, mitigate common issues such as vanishing or exploding gradients, and increase model performance.

## Regularization

You've seen regularization before in many other models including linear regression. For example, recall the L1 and L2 penalties which modify ordinary linear regression. These updated loss functions can help tune models so they do not overfit to the training data. For neural networks, you'll use a surprisingly similar process in order to achieve well trained models that are neither overfit nor underfit.


### Optimization

You'll also look at alternative optimization algorithms. These are of primary interest when one encounters local minimum. Knowing when one has hit such a pitfall can be challenging and typically requires experimenting with different optimization approaches and learning rates.

## Summary

Over the next couple of weeks, you'll extend your neural network knowledge by learning about evaluation, normalization, and regularization. Learning these will help you select the optimal model. 