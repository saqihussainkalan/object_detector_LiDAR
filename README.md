# object_detector
sources for object or obstacle detecting based on 1 channel LiDAR
# Object Detector using LiDAR Data

This repository contains the implementation of an **Object Detector** utilizing **LiDAR (Light Detection and Ranging)** data. The project demonstrates how to efficiently detect and classify objects in 3D space by processing point cloud data collected from a LiDAR sensor.

## Key Features:
- **LiDAR Point Cloud Processing**: Implements efficient handling and processing of raw LiDAR data.
- **Object Detection Algorithms**: Includes detection techniques for recognizing and classifying objects in the environment.
- **3D Visualization**: Provides visual outputs of detected objects using 3D visualization tools.
- **Modular Code Structure**: Well-organized and easy-to-follow code structure to facilitate further development and research.
  
## Technologies Used:
- **Python**: Core language for processing data and running algorithms.
- **Open3D/PCL (Point Cloud Library)**: For handling and processing point clouds.
- **Machine Learning**: Potential usage of ML models for classifying objects.
- **Matplotlib/Other Visualization Tools**: For generating visualizations and debugging.

## Use Cases:
- **Autonomous Vehicles**: LiDAR data plays a crucial role in obstacle detection and avoidance.
- **Robotics**: Detecting objects for robots to interact with their surroundings.
- **Surveying and Mapping**: Precision mapping of environments with obstacles in 3D.

## Setup and Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/sahilsaqi/object_detector_LiDAR.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the object detection module:
```bash
python object_detector.py
```
