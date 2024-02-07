# Chils-Safety-System-FYP
This repository contains the code and documentation for an advanced Artificial Intelligence based Child Safety System developed as a final year project. The system is designed to proactively identify and alert parents to unsafe activities involving their children. Below is a detailed overview of the key components of the project.

# 1. Dataset Creation
I created a dataset consisting of 13 distinct classes, including items such as child, scissors, knife, toys, fork, balls, heater, electric switchboard, spoon, among others. The dataset was created through a combination of data collection from Kaggle and manual acquisition from Google, including the capture of relevant child activity videos.

# 2. Data Preprocessing
To ensure uniformity and compatibility in the dataset, a Python script was implemented to standardize image formats to JPG and resize images to a standardized 640x640 pixels. Data augmentation techniques, including sharpening, blurring, and noise reduction, were applied to enhance the model training process.

# 3. Object Detection and Classification
The project leverages transfer learning on YOLO (You Only Look Once) to achieve robust object detection capabilities. The detected objects are further classified into safe and unsafe categories, providing a comprehensive understanding of the child's surroundings.

# 4. Child Object Interaction Algorithm
A Python algorithm was developed to monitor and analyze child movements. This algorithm calculates distances between the child and potentially unsafe objects, triggering alarms when the child approaches a hazardous item within a predefined threshold. This ensures a proactive response to potential safety risks.

# Usage
 To use the Child Safety System, follow these steps:
  1. Downlaod Model In your PC
  2. Download testing videos 
  3. Downlaod Python (ipynb) file to your pc (file named Run_Model.ipynb)
  4. Add path of model (Child_Safety_Model.pt) and testing videos to the Rum_Model.ipynb file.
  5. now run this file

# Requirements 
  1. Jupyter Notebook
  2. Python
  3. ultralytics (pip install ultralytics)
  4. pip install opencv-python


## If any one want dataset (contact me on whatsapp +92 342 0506599 Salman Ahmed)
