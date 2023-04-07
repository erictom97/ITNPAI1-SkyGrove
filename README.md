# SkyGrove

This project aims to detect trees from images of 2 cities in Scotland (Stirling and Edinburgh), United Kingdom using Faster RCNN and the state-of-the-art object detection algorithm YOLO (You Only Look Once). The YOLO algorithm is a real-time object detection system that can identify and locate objects within an image in a single pass while Faster R-CNN is a two-stage object detection algorithm that uses a Region Proposal Network (RPN) to generate region proposals (bounding boxes) for potential objects in the image.

The dataset of the 2 cities will be collected manually and will use YOLO for object detection to identify trees in the images. We will also perform data augmentation techniques such as flipping, rotation, and denoising to increase the size of our dataset and make the model more robust.

Once the models are trained, we will use it to detect trees in new images / unseen data. The output will be a bounding box around each detected tree, indicating its location within the image. We will also calculate the confidence score of each detection to determine the accuracy of our model.

SkyGrove will be a valuable tool for urban planning, modelling urban growth patterns and forestry management in the two cities. The project will provide insights into the distribution and density of trees in the cities, helping policymakers to make informed decisions on urban development and green space allocation. It can also be helpful to understand human impact on climate change.



  ![ezgif com-optimize](https://user-images.githubusercontent.com/40288848/227748171-1a8c2be9-0ea1-4a12-b3de-6323be75637a.gif)
