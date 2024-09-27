# EN3160 Assignment 1 - Intensity Transformations and Neighborhood Filtering

### Course: EN3160 - Digital Image Processing  
### Instructor: Ranga Rodrigo  
### Date: September 10, 2024

## Assignment Overview

This repository contains the solution for **Assignment 1** of the EN3160 module. The assignment covers several image processing techniques, including intensity transformations, gamma correction, histogram equalization, Sobel filtering, and image segmentation using the GrabCut algorithm.

### Key Tasks

1. **Intensity Transformation**  
   Implement intensity transformations to modify the brightness and contrast of images.

2. **Brain Proton Density Image**  
   Perform transformations to accentuate the white matter and gray matter regions of a brain proton density image.

3. **Gamma Correction in L*a*b* Color Space**  
   Apply gamma correction to the L plane in the L\*a\*b\* color space and analyze the changes in histograms.

4. **Vibrance Enhancement**  
   Increase the vibrance of an image by applying a custom intensity transformation to the saturation plane.

5. **Histogram Equalization**  
   Implement a custom function to carry out histogram equalization on images.

6. **Foreground Histogram Equalization**  
   Apply histogram equalization only to the foreground of an image and recombine it with the background.

7. **Sobel Filtering**  
   Perform Sobel filtering using both built-in and custom implementations.

8. **Image Zooming**  
   Implement image zooming using nearest-neighbor and bilinear interpolation methods.

9. **Image Segmentation Using GrabCut**  
   Segment the foreground and background of an image using the GrabCut algorithm and apply background blurring for enhancement.

## Instructions for Running the Code

To run the code in this repository, you will need Python 3.x and the following dependencies:

- `numpy`
- `opencv-python`
- `matplotlib`
- `scikit-image`

You can install the required dependencies by running:

```bash
pip install numpy opencv-python matplotlib scikit-image
