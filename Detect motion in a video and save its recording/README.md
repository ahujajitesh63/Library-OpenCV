# Project Title

Detect motion in a video and save its recording.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

The following methods are used in this project to show how to recognize faces and eyes in a video or live stream:
* The video or motion-containing feed is loaded first.
* In order to locate items in the video, it employs contours. 
* It then begins comparing two neighboring video frames using openCV. 
* It is able to detect moving objects since it looks for a change between successive frames. 
* An alert is set off and video recording begins as soon as motion is detected. 
* Consequently, a recording of the moving items will be available, and it will end after the entity has stopped moving. 
* This is similar to a surveillance system where the recording starts when anything moves.

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
$ cd Detect motion in a video and save its recording
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook - OpenCV - Notebook - OpenCV - Detect motion in a video and save its recording.ipynb
### Result
* Input: Raw video having motion

![](https://github.com/ahujajitesh63/Library-OpenCV/blob/main/Detect%20motion%20in%20a%20video%20and%20save%20its%20recording/Running%20-%2027539.gif)

* Output: Recording of detected motion

![](https://github.com/ahujajitesh63/Library-OpenCV/blob/main/Detect%20motion%20in%20a%20video%20and%20save%20its%20recording/Motion_detected_video23_50_49.gif)
