## Car Detection for Autonomous Driving

#### Problem Statement
Here we built an algorithm for real-time object (Car, Traffic signal) detection necessary for self-driving car. As a critical component of this project, we'd first build a car detection system. 

In this exercise, we will learn how "You Only Look Once" (YOLO) performs object detection, and then apply it to car detection. "You Only Look Once" (YOLO) is a popular algorithm because it achieves high accuracy while also being able to run in real-time. This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions. After non-max suppression, it then outputs recognized objects together with the bounding boxes.

Model details
 - Inputs and outputs: The input is a batch of images, and each image has the shape (m, 608, 608, 3).
 - The output is a list of bounding boxes along with the recognized classes. Each bounding box is represented by 6 numbers (pc,bx,by,bh,bw,c)(pc,bx,by,bh,bw,c). 
