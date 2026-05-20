# Image Preprocessing and Computer Vision Systems

## About

This repository collects engineering implementations spanning low-level digital image processing and advanced computer vision analysis. The notebooks demonstrate fundamentals of vision pipelines, matrix-level computation, and preparing visual data for downstream tasks such as segmentation, feature detection, and DCNN-based classification.

## Table of Contents (Notebooks)

### Image Processing Foundations
* **01_OpenCV_Basics**: Color spaces, 3D intensity analysis, histogram visualization.
* **02_Image_Math**: Point operations, LUT (Look-Up Table), image arithmetic, and masking.
* **03_Bit_Slicing**: Bit-plane decomposition and data significance analysis (MSB/LSB).
* **04_Histogram_Equalization_and_Color_Spaces**: Histogram stretching, CLAHE, HSV transforms.
* **05_Image_Binarization_and_Segmentation**: Otsu thresholding, iterative and adaptive binarization (Sauvola).
* **06_Image_Scaling_and_Interpolation**: Nearest-neighbor and bilinear interpolation implementations.
* **07_Advanced_Interpolation_Bicubic**: Bicubic interpolation with edge handling (padding).

### Detection and Morphology
* **08_Hough_Transform_Line_Detection**: Standard Hough Transform (SHT) for line detection.
* **09_Morphological_Operations**: Erosion, dilation, opening/closing, reconstruction, and Top-Hat/Bottom-Hat filters.
* **10_Fourier**: Fourier transform, frequency-domain filtering, window-based filter design.
* **11_Hough_Transform_Line_Detection**: Advanced linear structure detection (SHT vs. PHT) on real-world images.
* **12_Hough_Transform_Directional_Space**: Custom $a$-$b$ parameter space and singularity analysis.

### Segmentation and Classification
* **13_Image_Segmentation_Region_Growing**: Region growing (DFS) on medical MRI imagery.
* **14_Image_Segmentation_Split_and_Merge**: Quad-tree split-and-merge image decomposition.
