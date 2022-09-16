# Project Title

Detect faces and eyes in video.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

This project demonstrates how to recognise faces and eyes in a video or a live stream using following steps:
* It first loads the video or a stream having humans. 
* Then, using openCV and a pretrained model called cascade model, it analyses each video frame to find faces and eyes in a video.
* To detect more accurately, thresholding input to the model can be adjusted.
* The code then highlights the recognised faces and eyes in each frame and saves the frames as a new movie.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The things you need before installing the software.

* You need python 3.6.10 in your system

### Installation

A step by step guide that will tell you how to get the jupyter notebook up and running.

```
$ git clone https://github.com/ahujajitesh63/Library-OpenCV.git
$ cd Library-Machine-Learning
$ cd Detect faces and eyes in video
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook - OpenCV - Notebook - OpenCV - Detect faces and eyes in video.ipynb
### Result
* Input:

![](https://github.com/ahujajitesh63/Library-OpenCV/blob/main/Detect%20faces%20and%20eyes%20in%20video/Yoga-27084.gif)

* Output: Detected faces and eyes in a video

![](https://github.com/ahujajitesh63/Library-OpenCV/blob/main/Detect%20faces%20and%20eyes%20in%20video/faces_and_eyes.gif)
