# Web Element Object Detection using YOLOv8


## Overview

This repository contains the code and model for a web element object detection system using YOLOv8. The model is trained to detect various website elements, including 'button', 'field', 'heading', 'iframe', 'image', 'label', 'link', and 'text'. The training was performed using YOLOv8 Large (YOLOv8L) over 130 epochs.

## Model Deployment

The trained model is deployed and accessible through [ElementVisionizer on Roboflow Universe](https://universe.roboflow.com/web-element-object-detection/elementvisionizer/model/348). You can use this link to visualize and test the model's performance.
![Screenshot 2024-01-26 153219](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/13300bc8-b34e-4ee6-87a3-8418fc5c749c)

## Model Training

### Dataset
The model was trained on a dataset containing images annotated with the following labels:
- 'button'
- 'field'
- 'heading'
- 'iframe'
- 'image'
- 'label'
- 'link'
- 'text'

### Training Configuration
- YOLOv8 version: YOLOv8L (larger version)
- Epochs: 130
- imgsz: 640
- 
### Training Images
![Screenshot 2024-01-26 152628](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/41455955-fb19-499b-9848-87d86baffe1c)

![results](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/2eca9927-13c1-4460-ad53-7b4be5732fd6)

###  Metrics
#### Confusion matrix 
![confusion_matrix](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/d929b602-2cc7-4ebf-83dd-0c3ff933b099)

![confusion_matrix_normalized](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/f6cf4f34-b991-43fb-9314-f98cf6b97cee)

## mAP50: Mean average precision calculated at an intersection over union (IoU) threshold of 0.50
![Screenshot 2024-01-26 150824](https://github.com/gautham-balraj/ElementVisionizer/assets/121476362/4aea88b9-3bb0-425b-b64b-3b30f726ac8f)

