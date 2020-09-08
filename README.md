# Getting started with Tensorflow 2.0

Tensorflow is Google's public deep learning library, first released in 2015. Many would say that it's competed with PyTorch (released in 2016) for popularity, with PyTorch being the preferred library for most deep learning researchers over the past few years. However, just recently (2019), Tensorflow 2.0 was released which offered a much more user-friendly API and deep learning environment than its predecessor. Specifically, it interfaces with Keras now and offers several plug-and-play estimators as well as the ability to develop your own fancy deep learning architectures. 

In this tutorial, I'll cover the following items:

1. How to identify and frame a machine learning problem
2. How to get started right away with a plug-and-play estimator in Tensorflow 2.0
3. How to instantiate a more sophisticated architecture for learning
4. Saving, loading, and checkpointing models
5. Creating Tensorboard reports

## Identifying machine learning problems

In common parlance, machine learning can be synonymous with anything between the Terminator and the predicting movie recommendations. To muddy the waters even more, people may use "artifical intelligence", or (AI), instead of, or in combination, with "machine learning". The fact of the matter is that most of this is marketing, and really these problems all boil down to the same task of detecting patterns and making decisions with these patterns. For some reason, "artifical intelligence" is normally used more in the context of robotics and "machine learning" is normally used more in the context of prediction. But are founded in statistical approaches for detecting patterns.

With semantics out of the way, there are generally two classes of machine learning problems - **supervised** and **unsupervised** problems. The difference comes down what type of data we have.