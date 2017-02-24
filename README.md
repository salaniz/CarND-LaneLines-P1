#**Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Project to detect lane lines in images and videos of the road in front of a car.

Full description of problem and task: [TASK.md](TASK.md)  
Source code: [P1.ipynb](P1.ipynb)  
Writeup: [WRITEUP.md](WRITEUP.md)  
Videos: [videos_lanes/](videos_lanes/)  

## Summary of lane detection pipeline

Filter white/yellow pixels -> Canny edge detection -> Hough transform to get lines -> Extrapolate to solid lane lines  
<img src="./resources/yellow_white.jpg" width="200">
<img src="./resources/edges.jpg" width="200">
<img src="./resources/lines.jpg" width="200">
<img src="./test_images_lanes/solidYellowCurve2_solidlines.jpg" width="200">

Demo gif showing the lane detection on the challenge video:  
![alt text](./resources/challenge.gif)
