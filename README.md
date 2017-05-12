
monitoring-camera
====

OpenCV-based motion detector for video camera.

## Description

monitoring-camera is a program that monitors the video signal from a camera and is able to detect motion.

It is similar program to [motion](https://github.com/Motion-Project/motion), but it uses 
a background subtraction algorithm for motion detection that is included in OpenCV.
Functions are very limited comrared with motion.

## Requirement

* [OpenCV](http://opencv.org/)
* cmake

  ref: http://docs.opencv.org/2.4/doc/tutorials/introduction/linux_gcc_cmake/linux_gcc_cmake.html#linux-gcc-usage

#### Tested on

  * OpenCV 2.4.9.1
  * cmake 3.0.2
  * Armbian (Linux) (https://www.armbian.com/orange-pi-one/)
  * [Orange PI](http://www.orangepi.org/)

## Usage

To run:

    bgsub -vid 0


## Install

    $ git clone https://github.com/sdkn104/monitoring-camera.git
    $ cd monitoring-camera/src
    $ cmake .
    $ make
    $ make install
    $ make clean-all

## Author

[sdkn104](https://github.com/sdkn104)
