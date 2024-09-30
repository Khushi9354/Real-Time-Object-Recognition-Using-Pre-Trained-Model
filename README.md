# Object Detection with MobileNet SSD

## Overview

This project implements real-time object detection using the MobileNet SSD model. The code utilizes OpenCV and its deep learning module to detect various classes of objects from a webcam feed.

## Features

- Real-time object detection from webcam feed.
- Displays bounding boxes and confidence scores for detected objects.
- Supports multiple classes of objects.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject


## Install the required libraries:

pip install opencv-python numpy imutils

##Download the MobileNet SSD model files:

MobileNetSSD_deploy.prototxt.txt
MobileNetSSD_deploy.caffemodel

Place these files in the same directory as your script.

## Usage 
Run the script:

python your_script_name.py

The webcam feed will start, and the model will detect objects in real-time. Press Esc to exit.


## Code Explanation

The code loads the MobileNet SSD model and initializes the webcam.
Each frame is resized and processed to detect objects.
Detected objects are displayed with bounding boxes and labels.

## Classes
The model recognizes the following classes:

background,
aeroplane,
bicycle,
bird,
boat,
bottle,
bus,
car,
cat,
chair,
cow,
dining table,
dog,
horse,
motorbike,
person,
potted plant,
sheep,
sofa,
train,
tvmonitor,

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgments
OpenCV
MobileNet SSD


























