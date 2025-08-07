
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
![Koenigsegg_Jesko3](https://github.com/user-attachments/assets/dff6e8b9-206d-4077-92ec-1ef382398e33)
![Lambo_Huracan2](https://github.com/user-attachments/assets/b9a3a309-f505-40b7-af79-ffc4e07b3aef)
![McL_P1_1](https://github.com/user-attachments/assets/9e94e808-f5db-4a58-9336-d12f379f3cb9)
![Merc_S63_1](https://github.com/user-attachments/assets/e0ff6cbd-535e-457b-8e63-c00b1db5f1e9)
![Porsche_911T1](https://github.com/user-attachments/assets/b68c78cf-584f-4080-9034-b1b4f835c8c9)
