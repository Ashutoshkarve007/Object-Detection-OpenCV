# Custom Object Detection Using Keras and OpenCV

Build a System That Can Identify a Road Cracks a Given Image or Frame

Follow This page
    
    https://www.pyimagesearch.com/
    
We Have to take images and form corresponding .xml files for bounding boxes.

# Object detection: Bounding box regression with Keras, TensorFlow, and Deep Learning
    https://www.pyimagesearch.com/2020/10/05/object-detection-bounding-box-regression-with-keras-tensorflow-and-deep-learning/
    
# Logic of Project
R-CNN object detection with Keras, TensorFlow, and Deep Learning... Follow This Link.
      
      https://www.pyimagesearch.com/2020/07/13/r-cnn-object-detection-with-keras-tensorflow-and-deep-learning/

    1. Build a dataset using OpenCV Selective search segmentation
    https://www.pyimagesearch.com/2020/06/29/opencv-selective-search-for-object-detection/
    2. Build a CNN for detecting the objects you wish to classify (in our case this will be 0 = Smooth Road, 1 = Cracks, and 2 = Rifle)
    3. Train the model on the images built from the selective search segmentation
    4. When creating a bounding box for a new image, run the image through the selective search segmentation, then grab every piece of the picture.
    5. Run each piece of an image through the algorithm, and whenever the algorithm predicts the object you are looking for mark the locations with a bounding box
    6. If multiple bounding boxes are marked, apply Non-Maxima suppression to include only the box with the high confidence/region of interest (this part I am still figuring out… you will see my issue below)
    
 
 
