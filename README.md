# yolov3-object-detection
Real-time object detection using YOLOv3 pretrained model with OpenCV and Deep Learning.


YOLOv3 Pretrained Object Detection with OpenCV
Real-time object detection using a pretrained YOLOv3 model loaded via cv2.dnn. Detects 80 COCO object classes from any input image — vehicles, people, animals, and more — with bounding box visualization and Non-Maximum Suppression for clean output.

 Table of contents
Prerequisites & Installation
Download Pretrained Weights
How it Works — Architecture Overview
Detection Demo — BMW Car Example
Code Walkthrough
Console Output Explained
Supported COCO Classes
Prerequisites & installation
STEP 01
Install OpenCV
Needs opencv-python with DNN support enabled.
STEP 02
Download weights
237 MB pretrained weight file from the official Darknet repo.
STEP 03
Config + class file
yolov3.cfg and class_names (80 COCO labels).
STEP 04
Run detection
Pass any image path, adjust threshold, see annotated output.
bash — install dependencies
pip install opencv-python numpy # Download the pretrained weights (237 MB) wget https://pjreddie.com/media/files/yolov3.weights # Download config file wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg
