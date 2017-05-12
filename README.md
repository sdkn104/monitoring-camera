
monitoring-camera
====

OpenCV-based motion detector for video camera.

## Description

monitoring-camera is a program that monitors the video signal from a camera and is able to detect motion.

It is similar program to motion[https://github.com/Motion-Project/motion], but it uses 
a background subtraction algorithm for motion detection that is included in OpenCV.
Functions are very limited comrared with motion.

## Requirement

* OpenCV

## Usage

To run:
‘‘‘
bgsub -vid 0
‘‘‘

## Install

‘‘‘ 
$ git clone https://github.com/sdkn104/monitoring-camera.git
$ cd monitoring-camera/src
$ cmake .
$ make
$ make install
$ make clean-all
‘‘‘

## Author

[sdkn104](https://github.com/sdkn104)
