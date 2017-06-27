# Optical Flow

This is a sample code for extrating dense flow field given a video.  
This code is forked from [wanglimin](https://github.com/wanglimin/dense_flow)  

----
## How to build it
1. mkdir build
2. cd build
3. cmake ..
4. make

## How to use it
Usage:
./denseFlow_gpu -f test.avi -x tmp/flow_x -y tmp/flow_x -i tmp/image -b 20 -t 1 -d 0 -s 1
test.avi: input video
tmp: folder containing RGB images and optical flow images
