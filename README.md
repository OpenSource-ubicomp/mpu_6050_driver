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

2. [Connect](https://github.com/OpenSource-ubicomp/mpu_9250_driver/blob/master/image/Xavier%20AGX%20pin%20map.png) the MPU-9250 and MPU-6060 gyro sensors to the Jetson AGX Xavier board.
   
| Sensor Pin | Jetson AGX Xavier Pin |
|------------|------------------------|
| VCC        | 2                      |
| GND        | 6                      |
| SCL        | 28                     |
| SDA        | 27                     |




3. Clone this repository.
