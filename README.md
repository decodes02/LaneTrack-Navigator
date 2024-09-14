# LaneTrack Navigator

## Introduction
When driving, we rely on our vision to navigate, using road markings as continuous guides for steering. Similarly, when developing self-driving cars, one of the primary tasks is to create an algorithm that can automatically detect these lane lines. In this project, we use Python and OpenCV, an open-source computer vision library, to detect lane lines in images. OpenCV provides a range of useful tools for image analysis, making it ideal for this task.

## Overview
The tools we have are:
- **Color Selection**
- **Region of Interest Selection**
- **Grayscaling**
- **Gaussian Smoothing**
- **Canny Edge Detection**
- **Hough Transform Line Detection**

Our goal is to piece together a pipeline that:
1. Detects line segments in the image.
2. Averages/extrapolates the segments and draws them onto the image for display.
3. Applies this working pipeline to a video stream.

In addition, we incorporate **object detection** with **MobileNet SSD v3** to identify and classify objects within the driving scene, enhancing overall situational awareness.

## Features
- Engineered a sophisticated lane line detection system with OpenCV and cutting-edge image processing methods.
- Applied Gaussian smoothing and adaptive thresholding, coupled with region masking, to improve lane line visibility.
- Incorporated object detection using **MobileNet SSD v3** to identify and classify objects within the driving scene.

## Prerequisites
- Python 3.x
- OpenCV
- NumPy
- MobileNet SSD v3 model files
- Matplotlib (for visualization)

## Model Files
Download the pre-trained MobileNet SSD v3 model from [here](https://colab.research.google.com/drive/1tPeFIqipBS5pvOWW3ik0kmvREGdS0AXG?usp=sharing).

## Installation
```bash
pip install opencv-python
pip install numpy
pip install matplotlib

