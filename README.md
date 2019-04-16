# Autonomous_driving_Car_Detection

This project aims to build a car detection system using YOLO algorithm. you've mounted a camera to the hood (meaning the front) of the car,
which takes pictures of the road ahead every few seconds while you drive around.

ou've gathered all these images into a folder and have labelled them by drawing bounding boxes around every car you found. Here's an example of what your bounding boxes look like.

If you have 80 classes that you want YOLO to recognize, you can represent the class label $c$ either as an integer from 1 to 80,
or as an 80-dimensional vector (with 80 numbers) one component of which is 1 and the rest of which are 0. The video lectures had 
used the latter representation; in this notebook, we will use both representations, depending on which is more convenient for a 
particular step.

The project deals with two task:
1)Use object detection on a car detection dataset
2) Deal with bounding boxes
