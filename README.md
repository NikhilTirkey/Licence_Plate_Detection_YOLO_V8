# Licence_Plate_Detection_YOLO_V8
# License Plate Detection using YOLOv8

This project detects vehicle license plates using YOLOv8 trained on a custom annotated dataset in Google Colab.

## Features

* Custom YOLOv8 training
* License plate detection from images
* Bounding box prediction
* Trained custom model (`best.pt`)

## Dataset

Dataset is in YOLO format with:

* train
* valid
* test

## Training Results

* Precision: 0.986
* Recall: 0.987
* mAP50: 0.985

## Tech Stack

* Python
* YOLOv8
* Google Colab
* OpenCV

## Model Usage

```python
from ultralytics import YOLO

model = YOLO("best.pt")
model.predict("image.jpg")
```

## Sample Output

See uploaded prediction image in repository.

## Project Goal

Learning custom object detection workflow using YOLOv8 for computer vision applications.
