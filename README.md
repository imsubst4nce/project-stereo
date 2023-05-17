# project_stereo<br>

**A project based on the use of stereoscopic images for computer vision related tasks.**<br>

This project was implemented by me for the class of **Introduction to Image Processing - 4TTV414U** the **16/05/2023**.<br>
The notebook contains complete documentation about the subject of the project, the methods and the tools used.

# Project Parts<br>
1. Given 2 stereoscopic images(left/right), create 2 disparity maps using Block Matching algorithms(StereoBM and StereoSGBM).
2. Using the left image create 2 different depth maps using DenseDepth and MiDaS pretrained models.
3. Use 2 high-pass filters(Laplacian, Sobel) to test the previously generated disparity and depth maps in terms of edge-detection.

⚠ I do not own the stereo photos
[Link to photos](https://vision.middlebury.edu/stereo/data/scenes2014/)

> Special thanks to the creators of [DenseDepth](https://github.com/ialhashim/DenseDepth.git) and [MiDaS](https://github.com/isl-org/MiDaS.git)
