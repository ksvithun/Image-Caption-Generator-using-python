# Image-Caption-Generator-using-python

Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision.
we will build an image caption generator to load a random image and give some captions describing the image. We will use Convolutional Neural Network (CNN) for image feature extraction and Long Short-Term Memory Network (LSTM) for Natural Language Processing (NLP).

Dataset Information

The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. 
The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.
