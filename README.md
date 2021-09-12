
# Image Colorization

Image colorization using different softwares require large amount of human effort, time and skill.But special type of deep learning architecture called autoencoder has made this task quiet easy. Automatic image colorization often involves the use of a class of convolutional neural networks (CNN) called autoencoders. These neural networks are able to distill the salient features of an image, and then regenerate the image based on these learned features. 




![App Screenshot](https://tinyclouds.org/colorize/best/6.jpg)


## About autoencoders


Autoencoder are special type of deep learning architecture that consist of two networks encoder and decoder. The encoder, through a series of CNN and downsampling, learns a reduced dimensional representation of the input data while decoder through the use of CNN and upsampling, attempts to regenerate the data from the these representations. A well-trained decoder is able to regenerated data that is identical or as close as possible to the original input data. Autoencoder are generally used for anamoly detection, denoising image, colorizing the images. Here, i am going to colorize the landscape images using autoencoder.
  
![App Screenshot](https://miro.medium.com/max/600/1*nqzWupxC60iAH2dYrFT78Q.png)



### Dataset used

[landscape Color and grayscale images](https://www.kaggle.com/theblackmamba31/landscape-image-colorization)
