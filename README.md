# mpu_9250_ros_driver
ROS driver for the **MPU-6050** and **MPU-9250** IMU

## Project Description

This project demonstrates how to use NVIDIA's Jetson AGX Xavier board with 9-axis gyro sensors, specifically the MPU-9250 and MPU-6060, to read and utilize gyroscope and accelerometer data.

## Requirements

- NVIDIA Jetson AGX Xavier board
- MPU-9250 or MPU-6060 gyro sensors
- [Library Name and Version] - (Link to installation instructions)

## Installation

To get started with the project, follow these steps:

1. Set up the Jetson AGX Xavier board and install any necessary software.

2. Connect the MPU-9250 and MPU-6060 gyro sensors to the Jetson AGX Xavier board.
   
| Sensor Pin | Jetson AGX Xavier Pin |
|------------|------------------------|
| VCC        | 2                      |
| GND        | 6                      |
| SCL        | 28                     |
| SDA        | 27                     |


<img src="https://user-images.githubusercontent.com/51365114/119627750-716f3100-be47-11eb-8e83-686b23c2c161.png  width="200" height="400"/>
![image](https://github.com/jeonsion/tello_ros2/assets/57317636/9e5231a6-a6bb-4539-bbb9-1c8f8adb139a)

3. Clone this repository.
