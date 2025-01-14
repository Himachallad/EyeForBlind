# Eye for blind

In this capstone project, you need to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

 

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

The major steps that you have to perform can be briefly summarised in the following four steps:

Data Understanding: Here, you need to load the data and understand the representation.
Data Preprocessing: In this step, you will process both images and captions to the desired format.
Train-Test Split: Combine both images and captions to create the train and test dataset.
Model Building: This is the stage where you will create your image captioning model by building Encoder, Attention and Decoder model.
Model Evaluation: Evaluate the models using greedy search and BLEU score.
