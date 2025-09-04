# Landmark Detection & Robot Tracking (SLAM)

## Project Overview

SLAM (Simultaneous Localization and Mapping) implementation for a robot which lives in 2 dimensional world!  Robot moves in random direction by straight line until it comes close to a wall at which point it stops. It also can sense the x- and y-distance to landmarks.

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.*

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

## Table of Content
The project will be broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures.

- __Notebook 1__ : Robot Moving and Sensing

- __Notebook 2__ : Omega and Xi, Constraints 

- __Notebook 3__ : Landmark Detection and Tracking - Slam implementation and testing. 

- __robot_class.py__
- __helpers.py__


## Instructions

Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```


LICENSE: This project is licensed under the terms of the MIT license.
