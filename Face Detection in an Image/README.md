# Project Title

Face Detection in an Image.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

This project demonstrates how to recognise faces in an image using following steps:
* It first loads an image having humans. 
* Then, using openCV and a pretrained model called cascade classifier model, it analyses image to find faces in that image.
* To detect more accurately, thresholding input to the model can be adjusted.
* The code then highlights the recognised faces saves the image as a new image.

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
$ cd Face Detection in an Image
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook: Notebook - OpenCV - Face Detection.ipynb
### Result
* Input:
<img src="/Face Detection in an Image/people-1979261_1280.jpg" alt="image data" title="Image Data title">

* Output:
<img src="/Face Detection in an Image/Faces_Detected.png" alt="image data" title="Image Data title">


