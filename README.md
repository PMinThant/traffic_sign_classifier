# Traffic Light Classifier

In this project, you’ll use your knowledge of computer vision techniques to build a classifier for images of traffic lights! You'll be given a dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

## Classification Steps

In this project, I've pre-processed these images, extract features that will help distinguish the different types of images, and use those features to classify the traffic light images into three categories: red, yellow, or green. The tasks will be broken down into a few sections:
* Loading and visualizing the data.
* Pre-processing. The input images and output labels need to be standardized; that is, all the input should be of the same type of data and of the same size, and the output should be a numerical label. This way, I analyzed all the input images using the same procedures, knew what output to expect when I eventually classified a new image.
* Feature extraction. Next, I extracted some features from each image that will be used to distinguish and classify these images. This is where you have a lot of creativity; features should be 1D vectors or even single values that provide some information about an image that can help classify it as a red, yellow, or green traffic light.
* Classification and visualizing error. Finally, I wrote one function that uses my features to classify any traffic light image. This function will take in an image and output a label. I was also given code to classify a test set of data, compare your predicted label with the true label, and determine the accuracy of your classification model.

* Evaluate your model.My  classifier got >90% accurate and never classify any red lights as green.