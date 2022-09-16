# Project Title

Detect Text in an Image using openCV.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

This project shows how to use openCV to interpret text in images using following steps: 
* It detects text in images using tesseract library. 
* The words that are the clearest in the image are the simplest for the library to detect. As the words become smaller and more buried, 
it becomes more difficult for the library to identify the specific text. 
* Further, it demontrates how to modify the image to make it sharper and enhance the text detection by adjusting the threshold. 
* The text is highlighted and divided at every letter.

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
$ cd Detect Text in an Image using openCV
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook: Notebook - OpenCV - Detect Text in an Image.ipynb
### Result
* Input: Raw newspaper image:
<img src="/Detect Text in an Image using openCV/newspaper-433589_1280.jpg" alt="image data" title="Image Data title">

* Output: 
Letters outlined (without sharpening and threshoding):
<img src="/Detect Text in an Image using openCV/Letters_outlined.jpg" alt="image data" title="Image Data title">
Letters outlined (with sharpening and threshoding):
<img src="/Detect Text in an Image using openCV/Letters_outlined_with_thresholding.jpg" alt="image data" title="Image Data title">


