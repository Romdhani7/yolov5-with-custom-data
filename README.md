# yolov5-with-custom-data
n this project I made a special case which is the detection of ambulance army car police car and give it priority .
![image](https://user-images.githubusercontent.com/89159517/167204110-18accadb-b06d-45cc-8a67-3bab0b17632c.png)


CI CPU testing YOLOv5 Citation Docker Pulls
Open In Colab Open In Kaggle Join Forum

YOLOv5 🚀 is a family of object detection architectures and models pretrained on the COCO dataset, and represents Ultralytics open-source research into future vision AI methods, incorporating lessons learned and best practices evolved over thousands of hours of research and development.


See the YOLOv5 Docs for full documentation on training, testing and deployment.

Quick Start Examples
Install
Clone repo and install requirements.txt in a Python>=3.7.0 environment, including PyTorch>=1.7.

git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
Inference
YOLOv5 PyTorch Hub inference. Models download automatically from the latest YOLOv5 release.

import torch

# Model
model = torch.hub.load('ultralytics/yolov5', 'yolov5s')  # or yolov5n - yolov5x6, custom

# Images
img = 'https://ultralytics.com/images/zidane.jpg'  # or file, Path, PIL, OpenCV, numpy, list

# Inference
results = model(img)

# Results
results.print()  # or .show(), .save(), .crop(), .pandas(), etc.














Object Detection Algorithm — YOLO v5 Architecture
History and architecture of YOLO v5
![image](https://user-images.githubusercontent.com/89159517/167203515-6142633b-d731-4e94-93c5-aa1f8e442326.png)











Yolo V5 Architecture
CNN-based Object Detectors are primarily applicable for recommendation systems. YOLO (You Only Look Once) models are used for Object detection with high performance. YOLO divides an image into a grid system, and each grid detects objects within itself. They can be used for real-time object detection based on the data streams. They require very few computational resources.

History of YOLO

Yolov1 (Jun 8th, 2015): You Only Look Once: Unified, Real-Time Object Detection
Yolov2 (Dec 25th, 2016): YOLO9000:Better, Faster, Stronger
Yolov3 (Apr 8th, 2018): YOLOv3: An Incremental Improvement

Yolov4 (Apr 23rd, 2020): YOLOv4: Optimal Speed and Accuracy of Object Detection

Yolov5 (May 18th, 2020): Github repo (there is no paper as of Aug 1st, 2021)
