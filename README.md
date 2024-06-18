# OpenCV_Sparse Motion Field Tracker

## Description
The program was written in C++ language using OpenCV, and while tracking the feature points in a specific ROI in the video, the image to be attached to the area was given as an input, and the homography was calculated every time the feature points moved so that the image transformation was applied.

## Dependencies

* OpenCV 4.8.0
  * include "calib3d.hpp", "highgui.hpp", "imgproc.hpp", "video.hpp" for usage
* CVUI 2.7.0 (https://github.com/Dovyski/cvui)
  * install "cvui.h" and put into solution folder.

![결과 GIF](https://github.com/Jisu-Woo/OpenCV_SparseMotionFieldTracker/assets/162106530/7c21f7c6-b6d6-4c79-8206-e426e6236baf)
