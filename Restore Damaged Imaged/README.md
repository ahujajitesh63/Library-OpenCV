# Project Title

Restore Damaged Image.

## About The Project

The OpenCV package provides innovative ways to carry out a range of computer-vision-based activities. It may be used for object identification, facial recognition in real-time, object processing, and video capture, among other things.

This project demonstrates how to restore damaged Image in openCV using following steps: 
* It begins with grabbing a image to work with. In this scenario, it grabs an video of an owl. 
* Then it imports a masked version of an image which is masked manually over damages that need to be removed. (You can use any software such as paint for masking)
* Finally it restores the masked area by using the color scheme in the neighboring areas on mask and saves the restored image.
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
$ cd Restore Damaged Imaged
$ pip install notebook
$ pip install -r requirements.txt
$ python -m notebook
```
* Click and Run the Notebook: Notebook - OpenCV - Restore Damaged Imaged.ipynb
### Result
* Input:
Damaged image:
<img src="/Restore Damaged Imaged/owl_dam.png" alt="image data" title="Image Data title">
Damaged image after masking:
<img src="/Restore Damaged Imaged/owl_dam_mask.png" alt="image data" title="Image Data title">

* Output:Restored image of owl:
<img src="/Restore Damaged Imaged/barn-owl-2550068_1280.jpg" alt="image data" title="Image Data title">

