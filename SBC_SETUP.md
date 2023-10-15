# SBC_SETUP

1. Install ROS Noetic image (from ROBOTIS)
   - #### Raspberry Pi 3B+
     https://www.robotis.com/service/download.php?no=1738
     
   - #### Raspberry Pi 4B
     https://www.robotis.com/service/download.php?no=2066
     
2. Unzip the download file in SD card
   Use various image burning tools
   - #### Raspberry Pi Imager
     ```
     https://www.raspberrypi.com/software/
     ```
3. Configure Network Setting
   - #### Editing the 50-cloud-init.yaml
     ```
     sudo nano /etc/netplan/50-cloud-init.yaml
     ```
     And replace the WIFI_SSID and WIFI_PASSWORD with your wifi SSID and Password
