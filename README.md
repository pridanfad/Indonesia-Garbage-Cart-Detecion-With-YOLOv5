# Indonesia-Garbage-Cart-Detecion-With-YOLOv5


https://github.com/pridanfad/Indonesia-Garbage-Cart-Detecion-With-YOLOv5/assets/102144951/bd4d6919-43fc-4780-b25b-0728f2a6be6e

This repository contains the implementation of the YOLOv5 algorithm to detect typical South East Asia garbage cart. The steps involved in the process are outlined below:

## Steps

- **1. Compiling the dataset**
  - Acquiring the garbage cart images from google with web scrapping technique, conmbined with several images provided by Image and Video Data Analysis, Badan Riset dan Inovasi Nasional, Indonesia

- **2. Annotating the dataset**
  - The images annotated with labelImg.py
  - The label are consist of; 0 as gerobak (cart) and 1 as non-gerobak (not-cart)

- **3. Training the YOLOv5 Model**
  - The yolov5 model developed by ultralytics https://github.com/ultralytics/yolov5 with the architecture shown below
  ![YOLOv5 Architecture](https://github.com/pridanfad/Indonesia-Garbage-Cart-Detecion-With-YOLOv5/assets/102144951/e198c406-22ec-45c7-be84-2f34588135de)

 - **4. Result**
   - The model's performance is illustrated through three graphs, encompassing the Precision-Confidence Curve, F1-Confidence Curve, and Precision-Recall Curve.
   ![image](https://github.com/pridanfad/Indonesia-Garbage-Cart-Detecion-With-YOLOv5/assets/102144951/c0bec1cb-16e1-4211-be1b-2a68e387643c)

- **Important Notes**
  - The detected garbage type is commonly found in the Southeast Asian (SEA) region, with a particular prevalence in Indonesia.
  - Due to the limited number of garbage cart images in the dataset (below 150 images), the results were adversely affected.
