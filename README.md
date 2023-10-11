# AutoRace_2023

Written based on ROBOTIS_autorace_2020 

## Requirments
  1. Ubuntu 20.04
  2. ROS-Noetic
  3. OpenCV-4.5.0
  4. Tutrtlebot3 Setup
  5. ELP_Webcam (170 degree)


### 1. Ubuntu-20.04 install

  https://releases.ubuntu.com/focal/ 
  -> ubuntu 20.04 Desktop image Download
  ![스크린샷 2023-10-11 19 30 37](https://github.com/YeeeeeHo/AutoRace_2023/assets/139672321/b1a20bae-d384-4149-b0c0-84833e7b2bb8)


When the Download is complete
 -> Network connection


ctrl + alt + t -> Open terminal
In a route directory

### Follow from ROBOTIS-Emanual (Turtlebot3-Quick start Guid)
```
sudo apt update && sudo apt upgrade && wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_noetic.sh
chmod 755 ./install_ros_noetic.sh
bash ./install_ros_noetic.sh
```
### Install Dependent ROS Packages
```
sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \
  ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \
  ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \
  ros-noetic-rosserial-python ros-noetic-rosserial-client \
  ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \
  ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \
  ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \
  ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers
```
### Install Turtlebot3 Packages
```
sudo apt install ros-noetic-dynamixel-sdk && sudo apt install ros-noetic-turtlebot3-msgs && sudo apt install ros-noetic-turtlebot3
```






