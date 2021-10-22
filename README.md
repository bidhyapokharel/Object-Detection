# Object-Detection

So, basically we're trying to detect the Object in the mentioned images/videos.

# How

1. First, we'll use MobileNet SSD & DNN in OpenCV to build our object detector.
2. Then, we'll use OpenCV to load already trained tensorflow models.
3. We'll create the loop to draw a rectangle & put text in the frames/images. 
4. Finally we'll pass the images/videos to draw/detect/localize the object.



# Tools Used:

## 1. Image Classification/Recognition:
    - Based on salient feature, we'll classify the image to which category a image belongs to. Deep learnig algorithm that we'll be using for image classification is MobileNet.
    - ImageNet will be our dataset for image classification.
    
    
## 2. Object detection:
    - Based on salient features, object detection specifies the location of multiple objects in the image.
      1. Classification 
      2. Localization.
    - We'll use SSD.MobileNetv2 algorithm and COCO (80 classes) will be our dataset for object clasification.
    
    
