# Object-Detection-OpenCV
Object Detection With OpenCV:

    The purpose for a tool like this is to be able to detect objects in real time using a camera system.
    The Main Purpose of this Project is to detect objects for road survillance in wich we will detect cracks on road and other parameters.
    
    Object detection and Object Tracking is Done so Far

# Object Detection vs Image Classification**

**Image Classification** >> is the process of using an image as your input through your model, and that model detects similarities in the given image, to have an output of your desired class. This will result in and output of your class name and the probability score.

**Object Detection** >> is the process of using an image and or video feed as your input through your model, and that model detects any objects. This can happen with many different object detection methods. This will result in an output of bounding boxes, class name, and probability score.

To understand this flow of object detection we must understand every concept of image recognization and all the training models.

# Requirements

* `keras`
* `numpy`
* `pandas`
* `opencv`
* `matplotlib`

# Data
To be created

# Data Processing
* Before being fed into the neural network for training, each image was resized to (150,150,3)
* After resizing, edge detection was tried for each version in order to create images where guns are more distinctive than the latter. Using edge detection resulted in images with a shape of (150,150), which was then resized to (150,150,1) in order to be fed into the convolutional neural network

# Model Architecture
* [`Categorical Crossentropy was used because the model is used to predict between three classes (0 = Clean Road, 1 = Cracks, 2 = pitholes)`](https://towardsdatascience.com/cross-entropy-for-classification-d98e7f974451)
* [`Softmax output was used because this is a ternary classification problem`](https://machinelearningmastery.com/softmax-activation-function-with-python/)
* [`To ensure that training continued for more than 20 epochs learning rate was reduced to .0001`](https://machinelearningmastery.com/understand-the-dynamics-of-learning-rate-on-deep-learning-neural-networks/)
* 


# Reference
[Weapon Detection](https://github.com/HeeebsInc/WeaponDetection)
