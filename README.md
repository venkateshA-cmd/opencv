Image Enhancement
In this project, two image enhancement techniques are used in Python:

High-Boost Filtering
Adaptive Local Gamma Correction
1. High-Boost Filtering
High-Boost Filtering (or noise reduction) enhances the sharpness and details of an image.

Formula:

f_HB = (A - 1) × f_original + f_sharpened

In this project, Gaussian Blur is used to find the high-frequency components of the image.

2. Adaptive Local Gamma Correction
Adaptive Gamma Correction is used to improve the brightness of different areas of an image.

The gamma values less than 1 bring up the dark areas; and the gamma values greater than 1 brighten the bright areas.

Technologies Used
Python
OpenCV
NumPy
Matplotlib
Installation
Install the following libraries (required):

pip install opencv-python numpy matplotlib

Result
The High-Boost method enhances sharpness and edges; the Adaptive Gamma Correction method enhances the brightness in various parts of the picture.

