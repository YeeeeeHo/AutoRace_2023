#OpenCV_SetUp -> opencv 4.5.0

## Ctrl + Alt + T 
```
opencv_version
```
![스크린샷 2023-10-25 11 02 38](https://github.com/YeeeeeHo/AutoRace_2023/assets/139672321/1d7cb0f4-e456-4c01-ae99-370a79ad5778)


------
OpenCV_Update
```
sudo apt-get install -y cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libdc1394-22-dev build-essential mlocate
```
```
sudo add-apt-repository "deb http://security.ubuntu.com/ubuntu xenial-security main"
```
```
sudo apt update
```
```
sudo apt install -y libjasper1 libjasper-dev
```
```
wget -O opencv.zip https://github.com/opencv/opencv/archive/4.5.0.zip
```
```
wget -O opencv_contrib.zip https://github.com/opencv/opencv_contrib/archive/4.5.0.zip
```
```
unzip opencv.zip && unzip opencv_contrib.zip
```
```
mv opencv-4.5.0 opencv && mv opencv_contrib-4.5.0 opencv_contrib && mv opencv_contrib opencv
```
