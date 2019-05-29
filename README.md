# OpenCV 4.0 Tutorial
[![](https://img.shields.io/badge/opencv-v4.0.0-orange.svg)](https://opencv.org/)       [![](https://img.shields.io/badge/opencv-tutorial-brightgreen.svg)](https://docs.opencv.org/4.0.0/d9/df8/tutorial_root.html)

✒️ [中文版本](./README_CN.md)
## Introduction

This repository contains source code of OpenCV Tutorial application, the environment is python3.0 and opencv4.0.

## Sample
- **Image load**
```python
import cv2

src = cv2.imread("test.png")
cv2.namedWindow("input", cv2.WINDOW_AUTOSIZE)
cv2.imshow("input", src)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
<div align=center><img src="https://i.loli.net/2019/05/22/5ce4b40258c9155103.jpg" width=200></div>

- **Gray Image**
```python
gray = cv2.cvtColor(src, cv.COLOR_BGR2GRAY)
```

<div align=center><img src=https://i.loli.net/2019/05/22/5ce4b2ae1e7ce86434.png width=120>       <img src=https://i.loli.net/2019/05/22/5ce4b2ae220a248459.png width=120></div>



***More opencv4.0 tutorials plese follow the learning road as below*** 👇👇👇

## Learning Road ⛳️

***Annotation:***
- ✔️  **: Basic**
- ✏️  **: Attention**
- ❣️  **: Important**

No    | Description   | Annotation
:--------: | :--------: | :--------:
code_001 | [Load Image](python/code_001/opencv_001.py)   | ✔️
code_002 | [Gray Image](python/code_002/opencv_002.py)   | ✔️
code_003 | [Image Create](python/code_003/opencv_003.py)   | ✔️
code_004 | [Pixel Read and Write](python/code_004/opencv_004.py)   | ✔️
code_005 | [Image Pixel Arithmetic Operations](python/code_005/opencv_005.py)   | ✔️
code_006 | [Image Pseudo-Color Enhancement](python/code_006/opencv_006.py)   | ✔️
code_007 | [Image Pixel Operation (Logical Operation)](python/code_007/opencv_007.py)   | ✔️
code_008 | [Image Channel Separation and Merging](python/code_008/opencv_008.py)   | ✔️
code_009 | [Color Space Conversion](python/code_009/opencv_009.py)   | ✏️
code_010 | [Image Pixel Value Statistics](python/code_010/opencv_010.py)   | ✔️
code_011 | [Image Pixel Normalization](python/code_011/opencv_011.py)   | ✔️
code_012 | [Video Read and Write](python/code_012/opencv_012.py)   | ✔️
code_013 | [Image Flip](python/code_013/opencv_013.py)   | ✔️
code_014 | [Image Interpolation](python/code_014/opencv_014.py)   | ✔️
code_015 | [Draw Geometry](python/code_015/opencv_015.py)   | ✔️
code_016 | [ROI of Image](python/code_016/opencv_016.py)   | ✔️
code_017 | [Image Histogram](python/code_017/opencv_017.py)   | ✔️
code_018 | [Histogram Dqualization](python/code_018/opencv_018.py)   | ✏️
code_019 | [Histogram Comparison](python/code_019/opencv_019.py)   | ✔️
code_020 | [Histogram Backprojection](python/code_020/opencv_020.py)   | ✔️
code_021 | [Image Convolution](python/code_021/opencv_021.py)   | ✔️
code_022 | [Averaging and Gaussian Blur](python/code_022/opencv_022.py)   | ❣️
code_023 | [Median Blur](python/code_023/opencv_023.py)   | ✔️
code_024 | [Image Noise](python/code_024/opencv_024.py)   | ✔️
code_025 | [Smoothing Images](python/code_025/opencv_025.py)   | ✔️
code_026 | [Gaussian Bilateral Blur](python/code_026/opencv_026.py)   | ✔️
code_027 | [Mean-shift Blur)](python/code_027/opencv_027.py)   | ✔️
code_028 | [Image Integral Algorithm](python/code_028/opencv_028.py)   | ✔️
code_029 | [Fast Image Edge Filtering Algorithm](python/code_029/opencv_029.py)   | ✔️
code_030 | [Custom Filter](python/code_030/opencv_030.py)   | ✔️
code_031 | [Sobel Operator](python/code_031/opencv_031.py)   | ✔️
code_032 | [More Gradient Operators](python/code_032/opencv_032.py)   | ✔️
code_033 | [Laplace Operator](python/code_033/opencv_033.py)   | ✔️
code_034 | [Image Sharpening ](python/code_034/opencv_034.py)   | ✔️
code_035 | [USM Sharpen Algorithm](python/code_035/opencv_035.py)   | ✔️
code_036 | [Canny Edge Detection](python/code_036/opencv_036.py)   | ❣️
code_037 | [Image Pyramid](python/code_037/opencv_037.py)   | ✔️
code_038 | [Laplace Pyramid](python/code_038/opencv_038.py)   | ✔️
code_039 | [Image Template Matching](python/code_039/opencv_039.py)   | ✔️
code_040 | [Binary introduction](python/code_040/opencv_040.py)   | ✔️
code_041 | [Basic Thresholding](python/code_041/opencv_041.py)   | ✔️
code_042 | [OTSU Thresholding](python/code_042/opencv_042.py)   | ✏️
code_043 | [TRIANGLE Thresholding](python/code_043/opencv_043.py)   | ✔️
code_044 | [Adaptive Thresholding](python/code_044/opencv_044.py)   | ✏️
code_045 | [Binary and Smoothing](python/code_045/opencv_045.py)   | ✏️
code_046 | [Image Connectivity component](python/code_046/opencv_046.py)   | ✔️
code_047 | [Image Connected component state statistics](python/code_047/opencv_047.py)   | ✔️
code_048 | [Image Contours](python/code_048/opencv_048.py)   | ❣️
code_049 | [Bounding Rectangle](python/code_049/opencv_049.py)   | ❣️
code_050 | [Contour Area and Perimeter](python/code_050/opencv_050.py)   | ✏️
code_051 | [Contour Approximation](python/code_051/opencv_051.py)   | ✔️
code_052 | [Contour Centroid Calculate](python/code_052/opencv_052.py)   | ✔️
code_053 | [HuMoment for Contour Matching](python/code_053/opencv_053.py)   | ✔️
code_054 | [Contour Cricle and Ellipse fitting](python/code_054/opencv_054.py)   | ✔️
code_055 | [Convex Hull](python/code_055/opencv_055.py)   | ✏️
code_056 | [Fitting a Line](python/code_056/opencv_056.py)   | ✔️
code_057 | [Point Polygon Test](python/code_057/opencv_057.py)   | ✔️
code_058 | [The Largest Inner Circle](python/code_058/opencv_058.py)   | ✔️
code_059 | [Hoffman Line Detection](python/code_059/opencv_059.py)   | ✔️
code_060 | [Probability Hoffman Line Detection](python/code_060/opencv_060.py)   | ❣️
code_061 | [Hoffman Cricle Detection](python/code_061/opencv_061.py)   | ❣️
code_062 | [Dilation and Erosion](python/code_062/opencv_062.py)   | ❣️
code_063 | [Structuring Element](python/code_063/opencv_063.py)   | ✔️
code_064 | [Opening Transformation](python/code_064/opencv_064.py)   | ✏️
code_065 | [Closing Transformation](python/code_065/opencv_065.py)   | ✏️
code_066 | [Application of Opening and Closing Operations](python/code_066/opencv_066.py)   | ✏️
code_067 | [Top Hat](python/code_067/opencv_067.py)   | ✔️
code_068 | [Black Hat](python/code_068/opencv_068.py)   | ✔️
code_069 | [Morph Gradient](python/code_069/opencv_069.py)   | ✔️
code_070 | [Contour based on Morph Gradient](python/code_070/opencv_070.py)   | ✏️
code_071 | [Hit and Miss](python/code_071/opencv_071.py)   | ✔️
code_072 | [Defect Detecting-1](python/code_072/opencv_072.py)   | ✔️
code_073 | [Defect Detecting-2](python/code_073/opencv_073.py)   | ✔️
code_074 | [Extract the Maximum Contour and Coding Key Points](python/code_074/opencv_074.py)   | ✔️
code_075 | [Image Inpainting](python/code_075/opencv_075.py)   | ✔️