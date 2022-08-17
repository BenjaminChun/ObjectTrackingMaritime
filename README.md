# Object Tracking in the Maritime Environment

This paper aims to make use of DeepSORT to perform object tracking and compare that to other conventional object tracking algorithms. DeepSORT is an algorithm that makes use of Kalman filter to predict object motion across time and convolutional neural networks to calculate appearance descriptors to classify objects according to their appropriate classes. We used the metric Intersection Over Union (IOU) of bounding boxes produced by the algorithms and compared it to bounding boxes of the ground truth dataset. This metric allows us to measure the precision of the algorithm. However, this does not fully measure how well the algorithm is since we are missing the accuracy of associating objects across different frames.
