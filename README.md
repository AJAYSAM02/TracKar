# Vehicle-Counting-Classification-Detection-in-Day-to-Day-Traffic-

## ABOUT PROJECT
YOLO stands for You Only Look Once. 
It is a real-time object recognition algorithm. It can classify and localize multiple objects in a single frame. 
YOLO is a very fast and accurate algorithm for its simpler network architecture. 
YOLO works using mainly these techniques:
Residual Blocks – It divides an image into NxN grids.  
Bounding Box regression – Each grid cell is sent to the model. Then YOLO determines the probability of the cell contains a certain class and the class with the maximum probability is chosen.  
Intersection Over Union (IOU) – IOU is a metric that evaluates intersection between the predicted bounding box and the ground truth bounding box. A Non-max suppression technique is applied to eliminate the bounding boxes that are very close by performing the IoU with the one having the highest-class probability among them.  

We will use OpenCV’s DNN module to work with YOLO directly. DNN means Deep Neural Network. OpenCV has a built-in function to perform DNN algorithms.

In this project, we will detect and classify cars, HMV ( Heavy Motor Vehicle) , LMV (Light Motor Vehicle) on the road, and count the number of vehicles traveling through a road. And the data will be stored to analyze different vehicles that travel through the road.

We create two programs to do this project: 
The first one will be the tracker for vehicle detection using OpenCV that keeps track of every detected vehicle on the road.
The second one will be the main detection program.


