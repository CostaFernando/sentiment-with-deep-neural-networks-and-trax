# sentiment-with-deep-neural-networks-and-trax
[Coursera Natural Language Processing with Sequence Models](https://www.coursera.org/learn/sequence-models-in-nlp/) assignment: Sentiment Analysis using Deep Neural Networks with Trax library.

In course 1, you implemented Logistic regression and Naive Bayes for sentiment analysis. However if you were to give your old models an example like: This movie was almost good.

Your model would have predicted a positive sentiment for that review. However, that sentence has a negative sentiment and indicates that the movie was not good. To solve those kinds of misclassifications, you will write a program that uses deep neural networks to identify sentiment in text. By completing this assignment, you will:

* Understand how you can build/design a model using layers
* Train a model using a training loop
* Use a binary cross-entropy loss function
*Compute the accuracy of your model
* Predict using your own input

As you can tell, this model follows a similar structure to the one you previously implemented in the second course of this specialization.

Indeed most of the deep nets you will be implementing will have a similar structure. The only thing that changes is the model architecture, the inputs, and the outputs. Before starting the assignment, we will introduce you to the Google library trax that we use for building and training models.
Now we will show you how to compute the gradient of a certain function f by just using .grad(f).

* Trax source code can be found on Github: Trax
* The Trax code also uses the JAX library: JAX
