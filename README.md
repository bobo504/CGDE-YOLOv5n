# CGDE-YOLOv5
A real-time safety helmet-wearing detection algorithm
# Usage
1. Download this repository
2. Create a virtual environment python >= 3.8
3. Install Pytorch
4. pip install -r requrements.txt
# Code Description
1. dataset configure file: "data/hardhat_5k_3.yaml"
2. model configure files: "models/yolov5-helmet/*.yaml"
3. attention module files: "models/CBAM.py, extra_modules.py". They are registered in "yolo.py"
4. DCNV2, Bottleneck_DCN, and C3_DCN are defined in "models/common.py" and registered in "yolo.py"
# Dataset
The dataset and .pt files are available at: https://drive.google.com/drive/folders/1FQiGdvKdzO4o7g1jO9ts83ukQKRzs12h?usp=sharing
