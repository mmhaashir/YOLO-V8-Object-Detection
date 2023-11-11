# YOLO V8 Object Detection

## Introduction <a name="intro"></a>

This project implements object detection using YOLOv8 on a custom dataset created using Roboflow. YOLOv8, developed by Ultralytics, is a state-of-the-art real-time object detection system that can detect a wide range of objects in images.

## Table of Contents

- [**Introduction**](#intro)
- [**Dependencies**](#dep)
- [**Dataset**](#data)
- [**Installation**](#install)
- [**Results**](#results)
- [**Contribution**](#contr)
- [**Conclusion**](#conc)

## Dependencies <a name="dep"></a>

To run this code, you will need the following Python libraries:

  - Ultralytics
  - Roboflow

## Dataset <a name="data"></a>

  1. A single image, the link to which is provided in the notebook.
     
  2. A custom roboflow dataset which can be accessed ![here](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc)

## Installation <a name="install"></a>

1. Clone the repository:
   `git clone https://github.com/mmhaashir/YOLO-V8-Object-Detection.git`
   
2. Install the required dependencies:
   `pip install !pip install ultralytics==8.0.20 roboflow --quiet`

## Usage <a name="usage"></a>

To run the YOLO V8 Object Detection:

  1. Open the Jupyter Notebook provided in the project directory.
     
  2. Install the required dependencies

  3. Run the notebook.

## Results <a name="results"></a>

After runnning the notebook, you'll see the outputs in the form of images localized and classified in the outputs of the cells.

## Contributing <a  name="contr"></a>

Contributions to this project are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.

## Conclusion <a name="conc"></a>

This project showcases the use of YOLO V8 to perform a image localization, and classificatoin.

Feel free to experiment with different images, and datasets to gain deep understanding of YOLO.
