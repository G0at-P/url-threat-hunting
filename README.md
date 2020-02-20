# NLP analysis of url with Deep learning models
A project aimed at classifying event type with host and url. My way approaches this type of task is to 
leverage of power of Natural Language Processing techniques and Deep Learning models.


# Data Description
A dataset fetched from internal database system, which comes in a csv file. It contains several features and is ordered in the timeline. 

My goal of this project to undercover the way AMICO threat detection system works and provide new insight into threat hunting with the aid of NLP and Deep Learning Models.



# 3-gram Hash Values
I need to convert the text information into a vector format so that deep learning models could fit well. That's why hash values
comes into play. An high level idea behind 3-gram hash values is that by fixing the dimension of a word representation, any url can be converted into a sequence of consecutive 3 letters and then translated
into a mathematical vectors with pre-fixed length



# Building the Model
The main tool I use for developig deep neural networks is Keras. Keras uses Google's Tensorflow (TF) as the primary backend engine
can work with TF libraries when building and training models. Keras abstracts TF building blocks, allowing us to build a model 
layer by layer.

For more information, readers can refer to the official website of [Keras](https://keras.io/). 


# Outcome
By calibrating the models with an huge amount of effort, I conclude this model with 89.7% AUC without incurring an overfitting issue.