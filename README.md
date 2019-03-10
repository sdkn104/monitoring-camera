
monitoring-camera
====

OpenCV-based motion detector for video camera.

## Description

monitoring-camera is a program that monitors the video signal from a camera and is able to detect motion.

It is similar program to [motion](https://github.com/Motion-Project/motion), but it uses 
a background subtraction algorithm for motion detection that is included in OpenCV.
Functions are very limited compared with motion.

## Requirement

* [OpenCV](http://opencv.org/)
* [cmake](https://cmake.org/)

  see [OpenCV Guide](http://docs.opencv.org/2.4/doc/tutorials/introduction/linux_gcc_cmake/linux_gcc_cmake.html#linux-gcc-usage)

#### Tested on

  * OpenCV 2.4.9.1
  * cmake 3.0.2
  * [Armbian](https://www.armbian.com/orange-pi-one/) (Linux) 
  * [Orange PI](http://www.orangepi.org/)  Computer board

## Usage

To run:

    bgsub -vid 0

Configuration file:   bgsub.xml  in current directory

## Install

    $ git clone https://github.com/sdkn104/monitoring-camera.git
    $ cd monitoring-camera/src
    $ cmake .
    $ make
    $ make install
    $ make clean-all

## Acknowledgements

This program uses the following software:

* [Labelling.h](http://imura-lab.org/products/labeling/)

## Author

[sdkn104](https://github.com/sdkn104)

## License

This software is released under the [MIT](https://opensource.org/licenses/mit-license.php) License, see LICENSE.txt.
