## Advanced Lane Detection 

### Watch Here: https://www.youtube.com/watch?v=5tyxVKph3Zg&list=PLs_4rBValRlTVzyG5aOz_qvI3s-S9lPQd&index=2&ab_channel=NOKTURNALDEVELOPER

![Lanes Image](./examples/example_output.jpg)

The Project
---
1. **Camera Calibration:** Calculate the camera calibration matrix and distortion coefficients using a series of images of a chessboard.
2. **Distortion Correction:** Apply distortion correction techniques to raw images to achieve a more accurate representation of the environment.
3. **Binary Thresholding:** Utilize color transforms, gradients, and other image processing techniques to generate a thresholded binary image.
4. **Perspective Transform:** Implement a perspective transform to rectify the binary image into a "bird's-eye view", facilitating easier detection of lane lines.
5. **Lane Detection:** Identify lane pixels and utilize curve fitting techniques to precisely determine the lane boundary.
6. **Curvature & Vehicle Position:** Calculate the curvature of the identified lane and estimate the vehicle's position with respect to the center of the lane.
7. **Lane Visualization:** Warp the detected lane boundaries back onto the original image for visualization purposes.
8. **Output Display:** Generate a comprehensive visual output that displays the lane boundaries, along with numerical estimates of the lane curvature and the vehicle's position.
