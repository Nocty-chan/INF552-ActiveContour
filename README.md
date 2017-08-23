# INF552 - Segmentation with Active Contours #

This is an implementation of the active contour algorithm for segmentation for the INF552 Computer Vision class at Ecole polytechnique(X).

The demo application provides an interface for the user to define a rough polygon around the object to is to be segmented, and lets him iterate over the Active Contour algorithm.

## How to use ##
* Install OpenCV and CMake.
* `cmake CmakeLists.txt && make`
* `./images`
* The demo loads a test image to play with and displays color gradients along axis X and Y.
Select the window named `images`.
* Using the mouse and left-click, define a rough polygon around the object that needs to be segmented.
* When polygon definition is done, press any key on keyboard.
* When pressing once the keyboard, the vector indicating the next movement of the points defined by the polygon will appear, a second press on any key will make the points move.
* Keep pressing until the polygon is stabilized.

## Demo ##
