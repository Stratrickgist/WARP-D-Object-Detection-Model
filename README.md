This project focuses on object detection using YOLOv8, the latest iteration of the YOLO algortihm. 


The dataset comes from Kaggle(https://www.kaggle.com/datasets/parohod/warp-waste-recycling-plant-dataset), and is a Waste Recycling Plant (WaRP) dataset, and it contains images from an industrial source plant. It contains 3 main folders, each with their own specific purpose: Detection (WaRP-D), Segmentation (WaRP-S), and Classification (WaRP-C). 

The main objective is to create an Object Detection Model that can accurately predict the classes on a validation dataset. With that said, we will be focusing on the WaRP-D dataset, which contains 2452 images for training, and 522 images for validation. These images have full HD resolution (1920x1080). These images are already labelled, and these are divided into the following groups (https://github.com/AIRI-Institute/WaRP/blob/main/assets/WaRP-Categories.png):

![Categories](https://raw.githubusercontent.com/AIRI-Institute/WaRP/main/assets/WaRP-Categories.png)
