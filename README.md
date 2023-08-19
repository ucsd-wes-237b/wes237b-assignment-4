# WES 237B Assignment 4
## Lab
### Part 1: CUDA Hello World
* Provide a copy of your `myKernel()``  implementation.

* Succinctly explain the difference between the two lw implementations.

### Part 2: GPU-Accelerated Image Manipulation
1. Submit all of your final code for Part 2.

2. For each algorithm (greyscale, inversion, blur), which implementation has the best performance? Make a quantitative case.

## Assignment: CUDA for Familiar Tasks
### Part 1
Report the approximate execution times for OpenCV Sobel, CPU Sobel, and GPU Sobel, for different sizes.

You can use square sizes from 512 to 4096 (note: your code should still work for non-square sizes).

Note that for smaller sizes, the FPS will be limited by the camera FPS, and beyond 1024, the images will not display. If you wish, you can completely disable the display (comment out imshow in main.cpp) for all sizes to get a more stable result for the GPU.

### Part 2
Your final source code and the performance measures requested above.