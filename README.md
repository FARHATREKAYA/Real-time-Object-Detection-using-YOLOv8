# Real-time Object Detection using YOLOv5 and OpenCV

This repository contains a Python script that uses YOLOv5 and OpenCV to perform real-time object detection using the default camera on a device.

## Requirements
Python 3.6 or later
PyTorch 1.7.0 or later
OpenCV 4.4.0 or later
NumPy 1.19.3 or later
ultralytics==8.0.23 or later

## Installation
1. Clone the repository: 
```rb
git clone https://github.com/your_username/your_repository.git
```
2. Navigate to the repository directory:
```rb
cd your_repository
```
3. Install the required packages:
```rb
pip install -r requirements.txt
```
##Usage
1. Download a pre-trained YOLOv5 model from the official repository or train your own model using the YOLOv5 repository.
2. Save the model file (.pt) in the same directory as the Python script.
3. Update the model_path variable in the Python script to match the name of your model file.
4. Update the class_name_dict variable in the Python script to match the class names used by your model.
5. Connect a camera to your device.
6. Run the Python script:
```rb
python real_time_detection.py
```
7. Press q to quit the program.
