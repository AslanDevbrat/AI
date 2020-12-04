# Exercise: Build a GAN

In this exercise you'll be creating a GAN from scratch.

## Exercise Goals

This exercise is meant to help you:

* Understand the fundamentals of GAN architecture.
* More fully understand the difficulty in building and training GANs
* Combine models in Keras using the Model class
* Work with Keras functional API to add multiple inputs and outputs

## Exercise Notes


This exercise is one of the most difficult in this repo and may take several hours of work to complete. Additionally, GANs require significant amounts of compute power to behave well. You may wish to run training sessions overnight, but you may also want to invest in some cloud compute time on a serious GPU.  

The provided Jupyter notebooks contain much of the information you need to complete this exercise. However, you should also expect to look up information from the Keras docs, external reading material, and other sources. You are encouraged to search for information on your own.

Finally, this is not an exam. Correct answers are not provided. In fact, the exercise has enough ambiguity that many different answers will qualify as correct. You should be able to prove the correctness of your own answers using readily available tools—and in so doing you'll have learned quite a lot.

## The Exercise

The exercise is simple in description: build a conditional GAN for one of these two provided datasets:

1. Fashion MNIST
1. Regular MNIST

These datasets are similar enough to the provided CGAN for CIFAR that you can leverage much of that code, but different enough that some of the architectural patterns must change (e.g. black and white rather than color, different input image sizes).

In addition to accommodating the differences, you should experiment with different "best practices" for training GANs (will provide some links). We suggest you first get a basic GAN working, then modify the network to be a conditional GAN, then (once your CGAN is working well) experiment with the "best practices." Some tips, hacks, and tricks work and others may not. Each GAN is (somewhat) unique, and the same thing goes for different datasets. A trick that worked for others may not work for you, so don't be afraid to remove a "best practice" from your implementation and test it.
