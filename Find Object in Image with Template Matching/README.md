# Project Title

Find Object in Image with Template Matching.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

This project demonstrates how to detect objects in a picture using the template matchng process in openCV using following steps: 
* It begins with grabbing a picture to work with. In this scenario, it grabs an image of a stop sign and an Owl. 
* Then it obtains a template which is also loaded and it will be matched in an image. 
* After matching the template inside an image, the background is separated from the foreground using a basic isolation approach in openCV. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The things you need before installing the software.

* You need python 3.6.10 in your system

### Installation

A step by step guide that will tell you how to get the jupyter notebook up and running.

```
$ git clone https://github.com/ahujajitesh63/Library-OpenCV.git
$ cd Library-Machine-Learning
$ cd Find Object in Image with Template Matching
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook: Notebook - OpenCV - Find Object in Image with Template Matching.ipynb
### Result
* Input: Image:
<img src="/Find Object in Image with Template Matching/stop-634941_1280.jpg" alt="image data" title="Image Data title">
Template:
<img src="/Find Object in Image with Template Matching/stop_mask.png" alt="image data" title="Image Data title">

* Output: Object detected with template matching and filtered:
<img src="/Detect Objects with Masking using openCV/stop_detection_mask.jpg" alt="image data" title="Image Data title">


