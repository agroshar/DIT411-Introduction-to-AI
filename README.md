# Introduction_to_AI_Project

Classifying handwritten digits 

The idea behind the project is to train a convolutional neural network to classify images of digits. Then create an input box which is able to detect what digit is being drawn in real time.

The training data we want to use the MNIST dataset, which is a dataset of thousands of small square 28x28 grayscale images of handwritten digits from the range 0 up to 9. 

For building our machine learning model we intend to use PyTorch. We have chosen this framework because it is open-source and should supposedly be easy to work with.


Possible extensions:

Reduce the input space by PCA and then use K-Means clustering to classify unlabeled digit imagery and compare the algorithms.

Detect digits from a handwritten number, by detecting where to split the number into digits and then feed the digits into the classification.

Use the number detection from above to create a captcha where you are supposed to draw a number to confirm your a human.

Extend the original dataset by changing colours, resolution and/or skewing the images in order to create a more robust digit detection.

Go on to a harder image classification problem with larger images and more classes.

Extend the extraction of digits from a camera stream with more complex background.

