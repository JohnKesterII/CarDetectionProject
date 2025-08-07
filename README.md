
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

## Output

![Audi_A5_1](https://github.com/user-attachments/assets/56ef9e8e-16ac-4e6d-9e4d-1c9abcf94e24)
![Ferrari_F40_1](https://github.com/user-attachments/assets/99fdc07c-3e06-41a6-9fba-0cb18d140d63)
