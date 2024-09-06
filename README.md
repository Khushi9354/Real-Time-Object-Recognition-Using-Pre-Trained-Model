Using pre-trained MobileNet SSD for Real Time Multi-Class-Object Detection
There are two type of deep neural networks here.

Base network
detection network
MobileNet, VGG-Net, LeNet and all of them are base networks. Base network provide high level features for classification or detection. For classification we add a fully connected layer at the end of this networks. But if we remove fully connected layer and replace it with detection networks, like SSD, Faster R-CNN, and so on. In fact, SSD use of last convolutional layer on base networks for detection task. MobileNet just like other base networks use of convolution to produce high level features.

This module loads pre-trained model for multiclass object detection from a video feed. Besides MobileNet-SDD other architectures can also be used for the same.

GoogleLeNet
YOLO
SqueezeNet
Faster R-CNN
ResNet 

The above model establish the following arguments:

video: Path file video.
prototxt: Network file is .prototxt
weights: Network weights file is .caffemodel
thr: Confidence threshold.L

Runnning this file

Download the pretrained model files namely 'MobileNetSSD_deploy.prototxt' and 'MobileNetSSD_deploy.caffemodel' files.
Check if the video camera in your device works properly. Code switches it on automatically once the code starts.
Use the below commond to execute the python file:- python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel (if this doesn't work, try giving absolute paths or set project directory)

Workflow of dnn in OpenCV:

loading model--selecting backend--selecting target--reading frame from camera 
--converting image to blob--forwarding--post process
