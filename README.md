# Coloring B/W Portraits with Neural Networks
Faithful colorization of greyscale images by building a convolutional neural network model using keras with tensorflow as backend.

I present a convolutional-neural-network-based system that faithfully colorizes black and white photographic images without direct human assistance. I explore various network architectures, objectives, color spaces, and problem formulations. The final classification-based model I build generates colorized images that are significantly more aesthetically-pleasing than those created by the baseline regression-based model, demonstrating the viability of our methodology.

I review some of the most recent approaches to colorize gray-scale images using deep learning methods. Inspired by these, I propose a model which combines a deep Convolutional Neural Network trained from scratch with high-level features extracted from the InceptionResNet-v2 pre-trained model. Thanks to its fully convolutional architecture, our encoder-decoder model can process images of any size and aspect ratio.

Automatic colorization of gray-scale images using deep learning is a technique to colorize gray-scale images without involvement of a human. Conventional techniques used for colorizing images need human intervention, which is time-consuming. The project deals with deep learning techniques to automatically colorize greyscale images. The proposed technique uses deep convolutional neural networks and has a number of advantages. The technique will reduce manual work, speed up the process and improve the accuracy. 

![our_net](https://user-images.githubusercontent.com/36199181/39629949-721b3c72-4fcb-11e8-9e2d-d60f7ea99c48.png)


# Dataset Used
Due to hardware limitations, the CNN Model is trained on a very specific and small dataset containing limited images of male humans. The dataset contains a total of 175 images out of which 160 are the training images and 15 are test images.
The model produces satisfactory results corresponding to this dataset but runs equally well if the dataset is large (having all types of images both in categories and in quantity) and generates excellent results.

# Results
![result1](https://user-images.githubusercontent.com/36199181/39631856-0bb9051c-4fd1-11e8-8524-a159b32aedaa.png)



