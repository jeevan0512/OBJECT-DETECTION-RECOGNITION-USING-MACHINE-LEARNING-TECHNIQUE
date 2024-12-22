Features:
*Detects multiple object classes, including people, vehicles, and animals.
*Lightweight implementation using MobileNet-SSD.
*Real-time object detection through video streams.
*Configurable confidence threshold to filter weak detections.

Prerequisites:
Python 3.7+
OpenCV (Version 4.x recommended)
NumPy
imutils

Installation:
git clone https://github.com/your-username/object-detection.git
cd object-detection
pip install -r requirements.txt
python object_detection1.py --image <path_to_image> --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --confidence 0.5
python object_detection1.py --image images/example_01.jpg --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --confidence 0.5
