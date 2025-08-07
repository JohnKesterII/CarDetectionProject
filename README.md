
# Project Title

A brief description of what this project does and who it's for


## Installation

Install yolov8

```bash
  pip install ultralytics
```
Train AI models
```bash
yolo task=classify mode=train model=yolov8n-cls.pt data=carDataset epochs=50 imgsz=224
```
Validating AI model
```bash
yolo task=classify mode=train model=yolov8n-cls.pt data=carDataset epochs=50 imgsz=224
```
Predicting AI model
```bash
yolo task=classify mode=predict model=runs/classify/train#/weights/best.pt source=carDataset/test
```


