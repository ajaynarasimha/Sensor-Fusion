This repository contains my project work for the course [SensorFusion](https://www.udacity.com/course/sensor-fusion-engineer-nanodegree--nd313).

As part of this course, I have completed following projects:
1. [Lidar Obstacle Detection](https://github.com/ajaynarasimha/Sensor-Fusion/tree/main/Lidar_Obstacle_Detection): Detecting the obstacles using lidar pointcloud data 
2. [2D Feature Tracking](https://github.com/ajaynarasimha/Sensor-Fusion/tree/main/2D_Feature_Matching) : Tracking features from Camera images
3. [3D Object Tracking](https://github.com/ajaynarasimha/Sensor-Fusion/tree/main/3D_Object_Trracking) : Tracking vehicles using Camera and Lidar data to prevent collision
4. [Unscented Kalman Filter](https://github.com/ajaynarasimha/Sensor-Fusion/tree/main/Unscented_Kalman_Filter) : Estimate trajectory of multipl cars on highway using noisy data


More details on the course can found below

### Welcome to the Sensor Fusion course for self-driving cars.

[![Sensor Fusion](https://github.com/ajaynarasimha/Sensor-Fusion/blob/main/sensor_fusion.png)](https://www.youtube.com/watch?v=kXXeOlb-J-k)

In this course we will be talking about sensor fusion, whch is the process of taking data from multiple sensors and combining it to give us a better understanding of the world around us. we will mostly be focusing on two sensors, lidar, and radar. By the end we will be fusing the data from these two sensors to track multiple cars on the road, estimating their positions and speed.

**Lidar** sensing gives us high resolution data by sending out thousands of laser signals. These lasers bounce off objects, returning to the sensor where we can then determine how far away objects are by timing how long it takes for the signal to return. Also we can tell a little bit about the object that was hit by measuring the intesity of the returned signal. Each laser ray is in the infrared spectrum, and is sent out at many different angles, usually in a 360 degree range. While lidar sensors gives us very high accurate models for the world around us in 3D, they are currently very expensive, upwards of $60,000 for a standard unit.

**Radar** data is typically very sparse and in a limited range, however it can directly tell us how fast an object is moving in a certain direction. This ability makes radars a very pratical sensor for doing things like cruise control where its important to know how fast the car infront of you is traveling. Radar sensors are also very affordable and common now of days in newer cars.

<img src="sensor_comparision_chart.png" width="700" height="400" />

**Sensor Fusion** by combing lidar's high resoultion imaging with radar's ability to measure velocity of objects we can get a better understanding of the sorrounding environment than we could using one of the sensors alone.

