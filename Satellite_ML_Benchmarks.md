
# Benchmark Datasets and Models for Efficient Machine Learning on Satellites

This document provides a list of common datasets and models used for benchmarking efficient machine learning tasks on satellite platforms. The datasets are commonly used in tasks like object detection, segmentation, and inference offloading in Low Earth Orbit (LEO) satellites. 

## Datasets

1. **xView Dataset**
   - Large-scale geospatial dataset used for object detection tasks.
   - Ground Sample Distance (GSD): 0.3 meters.
   - Data Volume: 20 GB.
   - [Dataset Link](https://xviewdataset.org/)

2. **DOTA Dataset**
   - Dataset for object detection in aerial images.
   - GSD: 0.1 to 0.81 meters.
   - Data Volume: 34.3 GB.
   - [Dataset Link](https://captain-whu.github.io/DOTA/)

3. **UAVOD10 Dataset**
   - Aerial scenes including buildings, planes, and tracks for object detection.
   - GSD: 0.15 meters.
   - Data Volume: 0.9 GB.
   - [Dataset Link](https://datasetninja.com/uav-small-object-detection)

4. **Ship Detection Dataset**
   - A dataset used for detecting ships in the Atlantic Ocean.
   - Image resolution: Up to 10K x 10K pixels.
   - [Dataset Link](https://www.kaggle.com/rhammell/ships-in-satellite-imagery)

5. **Wildfire Segmentation Dataset**
   - Dataset for wildfire segmentation tasks.
   - [Dataset Link](https://github.com/MatteoM95/CEMS-Wildfire-Dataset)

## Models

1. **YOLO**
   - A popular object detection model used in many satellite-based detection tasks, such as ship detection.
   - Versions used: YOLOv3, YOLOv3-tiny for resource-constrained environments.
   - [YOLO GitHub Repository](https://github.com/AlexeyAB/darknet)

2. **U-Net**
   - A deep learning model widely used for segmentation tasks, especially for detecting geographical changes such as wildfires.
   - [U-Net GitHub Repository](https://github.com/zhixuhao/unet)

These datasets and models provide a comprehensive starting point for benchmarking machine learning tasks related to satellite data processing.
