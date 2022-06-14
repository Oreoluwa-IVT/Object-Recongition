# Detect Face/Objects with Open CV
In this project, we get to perform Object Recognition using a raspberry pi 4 and a compatible raspberry pi camera module.
Libraires and other resources are attached below.

<img src="Images/R.png" width="180" height="200"> <img src="Images/newcam.png" width="200" height="250"><img src="Images/pi2.png" width="360" height="250"><img src="Images/pi1.png" width="205" height="190">

## Getting Started...
The raspberry pi is a single board computer. This means everything the board requires for computing is on the board(RAM , CPU , Wifi Chip etc). Although, to interact with the board, we need some kind of input or output , just to know what's going on inside. Notice the ports arranged on the board. That is how we interact with the raspberry pi. In this project I will not be using a keyboard and mouse directly connected to the pi. Rather, I'll be using a Remote client (VNC Viewer) on my PC to connect and control my raspberry pi. Find out how to set up VNC with the raspbery pi using the links below.

#### Help Links

- [ ] [Raspberry Pi First Time Setup](https://www.youtube.com/watch?v=y45hsd2AOpw)  
- [ ] [Remote Access to Your Pi](https://www.youtube.com/watch?v=IfzBPi4FHpI)
- [ ] [How to Connect Camera to Raspberry Pi 4,3,1 Module B+ ](https://www.youtube.com/watch?v=IfzBPi4FHpI)
- [ ] [How to Connect Camera to Raspbery  Pi Zero , Zero W](https://www.youtube.com/watch?v=oo0A_yRrIxQ)



## Setting Up OpenCV
To run the OpenCV library, we have to make sure we're running at least python 3.7 preferrably.

#### <img src="Images/python.png" height=30 width=30> Check your Python Version
Use the command below 

```C
python --version 
or
python3 --version
```

#### Install Python3 
```C 
sudo apt-get install python3
```


## Adding OpenCV Librarieslibrary dependencies for face recognition
In this project ,we use two packages. Caer and OpenCV Contrib.

##### OpenCV
```
pip install opencv-contrib-python
```
##### Caer
```
pip install caer
```
##### On Raspberry Pi Terminal

```
sudo apt-get install libqtgui4 libqtwebkit4 libqt4-test
```

```
sudo apt-get install libatlas-base-dev
```
```
sudo apt-get install libjasper-dev
```

##### Library Dependencies for Face Recognition

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
sudo apt-get install cmake
sudo apt-get install gfortran
sudo apt-get install git
sudo apt-get install wget
sudo apt-get install curl
sudo apt-get install graphicsmagick
sudo apt-get install libgraphicsmagick1-dev
sudo apt-get install libatlas-base-dev
sudo apt-get install libavcodec-dev
sudo apt-get install libavformat-dev
sudo apt-get install libboost-all-dev
sudo apt-get install libgtk2.0-dev
sudo apt-get install libjpeg-dev
sudo apt-get install liblapack-dev
sudo apt-get install libswscale-dev
sudo apt-get install pkg-config
sudo apt-get install python3-dev
sudo apt-get install python3-numpy
sudo apt-get install python3-pip
sudo apt-get install zip
sudo apt-get clean

```
