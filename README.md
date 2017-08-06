# Segmentation with Active Contour algorithm
Implementation of the active contour algorithm for image segmentation, for the Computer Vision -INF552- course at Ecole polytechnique.

Coded in C++ using the OpenCV library.

## How to use ## 
1. `cd build/`
2. `make`
3. `./images` 
4. An example image appears, click on the image to define an initial polygon around the object to be segmented. 
5. When polygon definition is done, push any key to launch the gradient descent step.
6. Continue pushing any key to iterate over the gradient descent steps. 

