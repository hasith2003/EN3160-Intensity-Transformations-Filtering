# EN3160 - Image Processing Assignment 1

This repository contains my implementation for **Assignment 01** of the image processing coursework.

The assignment explores fundamental image processing techniques including intensity transformations, histogram processing, spatial filtering, interpolation, image segmentation, and edge-preserving filtering.

## Tasks

The repository covers the following tasks:

1. **Piecewise Linear Intensity Transformation**
   - Implementation of a custom intensity transformation function using user-defined breakpoints.

2. **Intensity-Based Tissue Enhancement**
   - Intensity transformations for highlighting white matter and gray matter in a proton-density brain image.

3. **Gamma Correction in L*a*b* Color Space**
   - Gamma correction applied to the lightness (`L*`) channel while preserving color information.

4. **Vibrance Enhancement**
   - Saturation enhancement in HSV color space using a nonlinear intensity transformation.

5. **Histogram Equalization**
   - Custom implementation of histogram equalization and comparison of intensity distributions before and after equalization.

6. **Foreground Histogram Equalization**
   - Foreground extraction using HSV-based thresholding followed by histogram equalization applied only to the foreground.

7. **Sobel Filtering**
   - Sobel filtering using:
     - OpenCV `filter2D`
     - A custom filtering implementation
     - Separable horizontal and vertical filtering

8. **Image Zooming**
   - Custom image zooming using:
     - Nearest-neighbor interpolation
     - Bilinear interpolation
   - Reconstruction quality evaluated using normalized SSD.

9. **GrabCut Segmentation and Background Blur**
   - Foreground/background segmentation using GrabCut.
   - Background blurring while preserving a sharp foreground.

10. **Bilateral Filtering**
    - Comparison between Gaussian and bilateral filtering.
    - Custom implementation of bilateral filtering and quantitative comparison with OpenCV.

## Technologies

- Python
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib

## Repository Structure

```text
EN3160-Image-Processing-Assignment-1/
│
├── images/             # Input images used in the assignment
├── EN3160_A01.ipynb    # Main Jupyter Notebook
├── README.md
└── requirements.txt